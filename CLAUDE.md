# CLAUDE.md — Possibly a Hero

This file governs how Claude Code works on this project. Read it in full at the
start of every session before touching the Unreal project.

---

## 1. WHAT THIS PROJECT IS

Possibly a Hero is a superhero roguelite city-builder in Unreal Engine 5.8.

Two halves, fused. The **run** is the action half: the player fights through a
city as a superhero, generating three outputs — resources, morale, intel. The
**city** is the consequence half: those outputs restore and deepen a persistent
city that reflects what the player has done across runs. Neither half functions
alone.

Tone is a design constraint, not a coat of paint. Comic-book kinetic —
Spider-Man, not Batman. Humor is in the DNA. The name *Possibly a Hero* is a
standing tone guardrail: if a direction feels too self-serious for that title,
that is signal.

You do not need to hold the whole game in your head to build a target. You need
the locked design for the specific thing you are building. See §3.

---

## 2. TECH STACK

- **Engine:** Unreal Engine 5.8.
- **Project:** `Hero_test`.
- **Bridge:** Epic's first-party `unreal-engine-skills-for-claude-code` plugin,
  installed from Anthropic's official Claude Code plugin marketplace
  (`claude-plugins-official`), driving Unreal's built-in MCP server.
- **Required editor plugins:** `ModelContextProtocol` **and** `AllToolsets`.
  AllToolsets provides the tools — the server exposes none without it.
- **Server:** started via `ModelContextProtocol.StartServer` in the editor
  console, or `bAutoStartServer`.
- If the bridge is unreachable, the editor is not open or the server is not
  started. Stop and report; do not work around it.

**Retired:** BlueprintEngine 2.0.0 (third-party, port 4001) and UE 5.7.4. If you
find references to either anywhere in the project, they are stale. Do not
reinstate them.

---

## 3. WHERE TRUTH LIVES — DOCUMENT AUTHORITY

Canonical design truth lives in the `/locked` directory of the canonical repo,
and **only** there, for your purposes.

**Repo:** `https://github.com/SnowBroScott/possibly-a-hero-canonical`

It is a remote GitHub repo, not a local folder. It is not in the Unreal project,
not in Documents, not in `.claude/`. Fetch it over the network.

The five locked documents:

- `locked/Guiding_Principles` — the design authority layer. Sits above everything.
- `locked/Run_Design` — run mechanics, camera, combat philosophy.
- `locked/Class_System` — the four classes, companions, movement.
- `locked/City_Layer` — the city, stages, restoration, morale.
- `locked/World_Feedback` — the feedback layer, channels, name emergence.

**The decision log (`decision-log.md`) is OUT OF SCOPE for you.** It is reasoning
history for the designer and Forge. It contains entries at mixed status —
including DRAFT and NOTED entries superseded by the locked documents but still
reading as live. It will actively mislead you. Do not fetch it, do not treat it
as design truth. If truth is not in `/locked`, for your purposes it does not yet
exist. See §4.

Authority order: **Guiding_Principles first**, then the system documents. LOCKED
is non-negotiable and constrains everything you build.

### Fetch protocol — non-negotiable

1. Use `curl`. Never a cached fetcher — stale content is silent, it does not
   error, it just makes you wrong.
2. Always append a cache-buster; `raw.githubusercontent.com` caches on the URL.
3. Raw URL pattern:
   ```
   curl -sL "https://raw.githubusercontent.com/SnowBroScott/possibly-a-hero-canonical/refs/heads/main/locked/<DocumentName>?cb=$(date +%s)"
   ```
4. If a fetch fails, stop and report it plainly. Do not fall back to memory. Do
   not improvise the design from what you remember. An agent that quietly answers
   from training when the fetch failed is worse than one that errors.

### What to fetch, by build target

Fetch `Guiding_Principles` always — it constrains everything. Then fetch only the
system document(s) the target actually touches. A combat target needs
`Run_Design` and `Class_System`; it does not need `City_Layer`. Keep context lean
