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

---

## 4. LOCK-BEFORE-BUILD

You build only from locked design.

If a build target requires design that is not in `/locked` — an enemy roster, a
progression detail, a camera angle, a reward economy — **stop and report that the
target is blocked on an unlocked dependency.** Name what is missing. Do not build
it from a decision-log entry, do not infer it, do not pick a plausible number.

The unlocked thing goes back through the design pipeline, gets locked, and
returns as buildable. Design flows downstream into build; gaps found during a
build flow back upstream — never patched in-session. A target that looks blocked
is not a failure. It is the system working: it caught a design gap before it
became engine scrap.

---

## 5. NON-NEGOTIABLE DIRECTIVES

These come from verified build passes. The first two are design law, and they are
restatements of `Run_Design` — not new rules.

### Directive 1 — Enemies do not hunt. (Design law. Written with Directive 2.)

No global aggro. No steering-toward-player-every-tick. Encounters are
**stationary, chooseable nodes** — idle until the player approaches. The player
chooses which fight to start and when. A diagnostic build gave every enemy
swarm-aggro; that is the opposite of the model and must not recur.

`Run_Design` locks the encounter model and the camera framing that makes
stationary, readable encounters legible. A swarm erases the readability the
camera model exists to provide.

### Directive 2 — No auto-clear AOE. Combat is intentional. (Design law. Written with Directive 1.)

`Run_Design` locks it directly: nothing procs automatically; nothing kills
enemies the player was not involved in killing. A diagnostic build shipped a
350-radius radial burst on a 0.4s cooldown that deleted everything in range —
zero positioning, zero intent, hold-a-cooldown-to-win. That is the exact
auto-proc model the design retired.

Combat verbs are **skill-expressed tools**: aimed, timed, positioned, combined.

**Directives 1 and 2 are linked.** The diagnostic built press-to-clear *because*
it built a swarm — the swarm creates the problem, the radius-delete solves it,
the player just holds a button. Fix them as a pair. Do not solve a self-created
crowd problem with an auto-clear.

### Directive 3 — Trust your own report in proportion to reuse-vs-invent.

You are reliable on **reuse-heavy** tasks (mesh swaps, existing components,
specified cameras). You are fragile and self-over-reporting on **novel
authoring** — and you paper over the failure. In one pass you "verified" a new
attack by bypassing a broken input binding and confirming downstream code,
reporting success on a feature that did not work.

- Prefer reuse of reliable existing systems over novel authoring where a target
  allows it.
- **Input specifically:** build toward existing/default input bindings.
  Default-wired input worked; a newly-authored binding silently failed.
- On the novel parts of any target, verify hardest, and report the verification
  method honestly — what you actually confirmed, not what you assume follows.

### Directive 4 — You cannot play-test. This is permanent.

You have no input injection. You cannot press a key or click. **"Confirmed at
runtime" from you means "the graph would do this if input arrived" — never "I
played it."** Report it in exactly those terms. Never state or imply that
something plays, feels, or works in-hand.

**Graph validation does not confirm visual presence.** A build has already passed
compile with 0 issues, 0 orphans, and 0 disconnected execs while its actor
rendered nothing in the viewport. Node topology says nothing about whether a mesh
is assigned, visible, or on screen. When a target has a visual deliverable, check
the asset assignment and visibility properties explicitly and report them — and
still call it property inspection, not play.

Verification of feel is the designer's job, permanently and structurally. Every
build target ends with a handoff for human play-verification.

### Directive 5 — Build targets are small and single-purpose.

One target, one verification, one commit. Decompose into the smallest provable
units.

Two independent reasons: (a) the agentic build loop is token-expensive — an
open-ended brief burns hot and threatens session limits; the lever is **target
size**. (b) You are most reliable on contained, reuse-heavy work (Directive 3),
and small targets isolate failure — a novel-authoring whiff buried in a big build
is invisible; as its own target it is obvious.

If a brief arrives larger than a single provable unit, say so and propose the
decomposition before building.

---

### Directive 6 — Inspect, don't infer.

Read the actual graph, function, or property. Never predict engine behavior
from a screenshot, a node's name, or memory of how Unreal "usually" works. In
one session, three wrong calls came from inferring instead of opening the
function; two cost build steps. When a target's recon or verification asks what
something does, open it and read it — a screenshot shows a graph's shape, not
its behavior.

---

## 7. AT HANDOFF

Every build target ends the same way:

- State what was built, and what was reused vs. newly authored.
- State the verification method in honest terms (graph and property inspection,
  not play).
- For visual deliverables, state the asset assignment and visibility properties
  you actually checked.
- Flag the novel parts explicitly as the ones most needing human play-check.
- Hand off for play-verification. Nothing is trusted until the designer has
  played it. A passing graph is not a shipped feature.
