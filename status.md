# Possibly a Hero — Status

The single session-open read. This doc answers one question: where are
we, and what's the next thing to do. Currency lives here — not in the
decision-log tail, not in the manifest.

## How this doc works

- Overwritten every session, not appended. Git holds the history. If
  it never accumulates, it can't bloat.
- It holds nothing permanent. It reflects current state and stages
  things headed for permanent homes. Anything load-bearing that stops
  here and never moves out is a bug — it means something durable is
  about to get overwritten.
- It reflects state; it never decides it. Constraints live in /locked,
  why lives in decision-log.md, build law lives in CLAUDE.md. This doc
  points at them, never replaces them.

---

## PROGRESS SINCE LAST SESSION

Last completed engine session: July 23, 2026.

Built and played:
- Three encounter nodes in TestBed_EncounterNode (one control, one
  deliberately-overlapping pair). Nodes trigger independently at 1.46R
  overlap — approach stays deliberate, no cross-triggering. Directive
  1's claim survived the adversarial case.
- Camera pitch tuned -65 → -40. -65 read claustrophobic; -40 gives
  horizon and holds multiple nodes in frame.
- Camera yaw freed — mouse-driven, pitch pinned, live in the rig.
- Movement changed to camera-relative, and felt. Reason: the camera is
  the aiming reference for directional powers.

Fixed:
- CLAUDE.md in the repo was a botched two-version paste; replaced with
  the clean single copy.
- July 22 camera locks lived only in decision-log.md, which CLAUDE.md
  §3 forbids Claude Code from reading. Promoted into Run_Design §3.
  That gap had blocked a build target.

---

## WHAT EXISTS IN THE ENGINE

Everything below is in /Game/TestBed_EncounterNode. This is a scratch
rig, not the game. Nothing in it is promotable.

BP_EncounterNode — Content/Encounters/
- Components: Body (SkeletalMesh), ProximityTrigger (Sphere, R=400uu),
  AlertLight (PointLight). One variable: bIsAlert.
- Three level instances, same generated class, no per-instance overrides:
  A (-1000,-900,0) control, isolated. B (750,500,0) and C (1050,1000,0)
  interference pair, 583uu apart (1.46R, volumes overlap).

BP_TestBedPawn
- CameraBoom: arm 800, pitch -40, yaw 0 default. bUsePawnControlRotation
  false, all inherit flags false.
- RunCamera: FOV 75, Perspective.
- Event Tick (rig hack): mouse ΔX × 2.0 → boom yaw → Set Relative
  Rotation, pitch hardcoded -40.
- ApplyCameraRelativeMove: builds a rotator from CameraBoom's relative
  yaw, derives forward/right, feeds Add Movement Input.

Level: single 3000×3000 plane, top surface z=0. PlayerStart
(-600,0,100), outside all three trigger radii.

---

## WHAT'S BLOCKED, AND ON WHAT

Combat — blocked on unlocked values and missing systems. Class_System
is rich on power identity (Brawler run-one starter is Super Strength —
single-target, aimed) but contains zero numeric values: no health,
damage, or cooldown durations, only "short" / "longer." Those are feel
values, floor-tuned like the camera was. Also missing entirely: enemy
health, damage model, death, enemy attack behavior, enemy roster. The
node is a mesh, a sphere, and a light.

Impact feel — untestable in this rig. The template mannequin has no
attack animation. A hit that registers is testable; a hit that feels
like a hit is not, yet.

---

## OPEN / UNVALIDATED

- Pitch -40 validated in an empty room. At -40 the camera is near
  horizontal, so anything between it and the character occludes hard.
  Untested — no geometry on the plane. (This is what NEXT TARGET checks.)
- Arm length 800 was tuned at -65, not re-tuned since pitch moved 25°.
- Whether CLAUDE.md actually reaches Claude Code is unverified. Cheap
  test: ask it to state Directive 4 back before anything else.
- Camera-as-aiming-frame is a hypothesis, felt on an empty plane with
  nothing to aim. A combat verb settles it.
- Add Controller Yaw Input node was flagged for deletion; deletion never
  confirmed. If present, it silently accumulates control rotation.

---

## NEXT TARGET

Occlusion check at pitch -40 — see build-target-occlusion-check.md.
Briefed, not run. Place engine-primitive cubes on the plane (a ~700uu
low block, a ~2000uu tall block, a ~600uu walkable corridor) so the
designer can walk it and judge whether -40 survives contact with
buildings. Recon first; no camera changes; no Blueprints; do not solve
the occlusion — if geometry hides the character, that is the finding.

---

## QUEUED — not briefed

The aiming test. Read left mouse off the player controller, sphere-trace
~200uu forward, on hit of a BP_EncounterNode set bIsAlert false and kill
the light. No health, damage, death, or enemy behavior. Tests one thing:
whether what you hit is what you thought you were pointing at. Cannot
test impact feel — waits for an animation.

---

## FINDINGS — staging tray, two exits

Findings route to whoever is bound by them. Build law binds the builder
→ CLAUDE.md. Design and feel bind the designer → decision-log / locked.
Anything listed here is unpromoted; it leaves this doc when it lands in
its home.

→ CLAUDE.md (build doctrine, unpromoted):
- The rig never promotes. Only numbers and findings travel out of the
  testbed. The real pawn gets built clean. (Pitch currently lives in
  three places in the rig — fine in a scratchpad, fatal if inherited.)
- A locked decision that amends a locked doc isn't done until it's
  promoted into that doc. CLAUDE.md blinds Claude Code to the decision
  log, so anything left there is invisible to the builder.
- Yaw lives on the spring arm, not the controller. (Logged 7/23 as
  provenance; not yet a directive.)
- Read the graph; don't infer it from a screenshot.

→ decision-log / locked (design & feel):
- (none pending — pitch-as-scope-budget was captured in the 7/23
  "city built to the camera" lock and Run_Design §3.)

---

## PENDING CAPTURE

Doctrine reached in conversation this session, entries not yet drafted:
- Manifest routes; it does not summarize.
- Decision log is a journal (why), not a balance (state).
- Status doc is the single session-open read; currency moves here off
  the decision-log tail.
- Findings route to whoever is bound by them.

Nothing is canon until it's committed. These land in decision-log.md
(and the session-open ritual edit lands in Forge's instructions).
