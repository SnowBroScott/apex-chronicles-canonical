DECISION LOG ENTRY

DECISION: Run Initiation Loop — Corrected Structure

The run initiation sequence is as follows:
1. Player initiates new run
2. Player selects class
3. Player selects starting offensive power (only if more than one option is
   unlocked for that class)
4. Map loads
5. Intro scene plays — third person, brief, cinematic. Hero arrives via their
   class movement type.
6. Camera swings up to isometric offset play mode
7. Run begins

Class-specific intro animations:
- Brawler: leaps into frame, lands hard, camera swings up
- Speedster: blurs in, camera snaps up with motion blur
- Blaster: teleports in, hard cut to isometric
- Tactician: rolls in on vehicle, camera lifts and settles

The camera transition is not triggered by movement power selection. It is the
cinematic expression of a class choice already made. Class selection occurs
before map load. The intro scene is the payoff of that choice, not the moment
of it.

DATE: May 3, 2026

WHY: Class selection as a pre-map menu moment keeps the intro scene as pure
cinematic payoff rather than a UI moment. Each class arrival animation
communicates identity immediately and distinctly before a single enemy is
encountered.

REPLACES: Run camera transition — third person intro, isometric gameplay.
That entry implied movement power selection triggered the camera transition.
This entry supersedes that framing. The transition is class-driven, not
selection-driven.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Support Pool finalized at eight supports across three categories —
Combat: Reflexes, Power Surge, Blast Radius, Precision Strike, Rapid Recovery;
Utility: Overdrive, Fast Track; Safety: Last Stand. Pool is class-agnostic.
All names are comic book native.

DATE: May 3, 2026

WHY: Generic stat language replaced throughout with comic book kinetic
terminology that is instantly legible to roguelite players without explanation.
Pool is designed to be class-agnostic — every support has standalone value
regardless of primary or hero power combination, and no support encroaches
on class-specific identity.

REPLACES: Prior support naming using generic stat-based language.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Hero Powers pool finalized at eleven powers — shared pool, fully
random: Magnetism, Freeze Frame, Tempest, Tremor, Rift, Toxin, Sonic Scream,
Gorilla (Brawler class summon), Double Time (Speedster class summon), Specter
(Blaster class summon), Sentinel (Tactician class summon). No mission-type
biasing. Class summons are unique per class.

DATE: May 3, 2026

WHY: Every hero power is designed to have standalone offensive value before
combo value. Full randomness is intentional — ridiculous combos are a feature,
not an edge case. Class summons are native to each class identity. Light
manipulation was cut due to unclear mechanics and overlap with Sonic Scream.
Toxin replaces Venom to eliminate IP adjacency concerns.

REPLACES: Light manipulation (cut); Venom (replaced by Toxin).

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Support Pool and Hero Powers — Complete Layer Definitions

NOTE: Support pool naming in this entry uses earlier generic stat language.
The finalized comic book native naming is established in the Support Pool
entry above and supersedes this entry's support pool naming. Hero power
content remains valid.

Three-layer system confirmed:
- Class Primary — class-specific offensive powers
- Hero Powers — offensive with utility upside, mid-run pickups, shared pool,
  fully random
- Support Pool — genre-legible enhancements, class-agnostic

HERO POWERS (shared pool, fully random):
1. Magnetism — pull enemies together, redirect projectiles, strip weapons
2. Freeze Frame — brief local time dilation; everything stops, player doesn't
3. Tempest — lightning strikes, wind gusts, localized storms. Environmental
   and atmospheric — the storm answers the hero rather than coming from them.
   Thor's lightning bolt, not force lightning.
4. Tremor — fissures, earthquakes, terrain as weapon
5. Rift — displaces and moves enemies around the map; intentionally chaotic
6. Toxin — damage over time, spreads between enemies
7. Sonic Scream — stuns, disorients, chain damages
8. Class-Specific Summons (unique per class):
   - Brawler: Gorilla — animal companion
   - Speedster: Double Time — speed clone
   - Blaster: Specter — spectral ally, phases through walls
   - Tactician: Sentinel — combat drone

Hero power design principles:
- Every hero power has standalone offensive value before combo value
- Pool is fully random — no mission-type biasing
- Ridiculous combos are a feature, not a bug

Cuts (with reasoning):
- Hard Light Constructs — too IP-adjacent (Green Lantern)
- Self Duplication (standalone) — absorbed into Speedster class summon
- Size Manipulation — doesn't fit isometric offset gameplay
- Intangibility — overlaps with invisibility in support layer
- Probability Manipulation — doesn't fit Apex tone
- Black Hole — covered by Blaster primary gravity well
- Dimensional Pocket — consolidated into portal creation
- Density Wave — doesn't fit
- Adrenaline — renamed Attack Damage, moved to support pool

ELEMENTAL DISTINCTION NOTE:
Elemental Surge (Blaster class primary, lightning variant) and Tempest are
not redundant powers. Elemental Surge is force lightning — directed, precise,
projected from the hero's body at a target. Tempest is Thor's lightning bolt —
called from above, environmental, affects the space rather than a single
target. They share an element. They are emphatically not the same power.
A Blaster running both in the same run is not doubling up — they are a
precision energy projector who can also call storms.

COMBO SYSTEM NOTE:
Combos are discovered organically during runs — Vampire Survivors style.
The right combination of powers held simultaneously triggers a combo —
unannounced, emergent, discoverable by accident. Once discovered, the combo
is permanently logged in the Hero's Lair including what was required to
trigger it. The lair does not unlock combos. It records them.

Example of emergent combo discovery — Blaster + Elemental Surge (lightning)
+ Tempest: The Blaster projects directed lightning from below while a storm
responds from above. Two directions. Same frequency. Discovered in a run,
logged in the lair. Rex Flynn has a video about the first time someone found
it. Twelve million views. Unhinged thumbnail.

DATE: May 3, 2026

WHY: Hero powers stay offensive with utility upside to protect class identity
and keep the three layers distinct. A fully random hero power pool creates
genuine surprise and ridiculous combo potential — standalone value for every
power is the baseline protection against dead draws.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Class Offensive Suites — All Four Classes

PRIMARY LAYER DETAILS:

BRAWLER (Movement: Leaping)
- Starter: Super Strength — single target bruiser
- 10 runs: Shockwave / Impact Burst — AOE
- 30 runs: Elasticity / Stretch — mid-range combat

SPEEDSTER (Movement: Super Speed)
- Starter: Speed Strike — single target rapid combo
- 10 runs: Velocity Slam — momentum/skill-based impact
- 30 runs: Tornado — AOE environmental chaos

BLASTER (Movement: Teleportation)
- Starter: Energy Blast — single target precision
- 10 runs: Elemental Surge — choose fire, ice, or lightning per run, each
  with distinct status effects. Directed elemental projection — force
  lightning, concentrated fire, precision ice. Comes from the hero's body
  and is aimed at targets. Not environmental, not atmospheric.
- 30 runs: Gravity Well — AOE tactical, pulls and detonates

TACTICIAN (Movement: Vehicle)
- Starter: Rifle — single target precision
- 10 runs: Deployable Turrets — utility and area control
- 30 runs: Rocket Launcher — AOE destruction

UNLOCK STRUCTURE (all classes):
- Unlocks are cumulative and permanent across runs
- Failed runs do not count toward unlock progress but do not reset it
- Unlock thresholds: 10 and 30 successful runs with that specific class

DATE: May 3, 2026

WHY: Three primary offensive options per class — single target,
utility/tactical, and AOE — each represent a distinct playstyle. Separating
primary and support layers keeps class identity clean while the shared support
pool generates combinatorial variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The class system uses four per-run selectable classes — Brawler
(movement: Leaping), Speedster (movement: Super Speed), Blaster (movement:
Teleportation), and Tactician (movement: Vehicle). Class selection occurs at
the start of each run and is not a permanent character assignment.

DATE: May 3, 2026

WHY: Per-run selection preserves pick-up-and-play accessibility. Players can
experiment freely without commitment, while the mastery system rewards loyalty
separately from class choice itself.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Movement is class-locked and not player-selectable. Flight and wall
crawling are removed from the movement pool entirely. The Tactician's vehicle
is permanent for the duration of a run — no exit mechanic exists.

DATE: May 3, 2026

WHY: Flight removed due to build complexity, balance issues, and isometric
offset incompatibility. Wall crawling removed due to verticality requirements
and IP adjacency concerns. Locking movement to class simplifies systems and
strengthens class identity.

REPLACES: Flight and wall crawling as movement pool options — both removed.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Each class begins with one offensive power. A second offensive
option unlocks after 10 successful runs with that class. A third unlocks after
30 successful runs. Unlocks are cumulative and permanent — they never reset.
Failed runs do not contribute to progress but do not reduce it.

DATE: May 3, 2026

WHY: Cumulative permanent tracking aligns with the "consequence without
punishment" core principle — players are rewarded for mastery without being
penalized for failure or variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The Guardian is removed as a standalone class. Defensive and
protective powers previously associated with the Guardian archetype are
redistributed into the power pools of all four classes at lower probability.

DATE: May 3, 2026

WHY: Removing Guardian streamlines the class roster without eliminating its
design contribution. Distributing defensive powers across all pools preserves
tonal and mechanical variety.

REPLACES: Guardian as a standalone selectable class.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Run Camera Transition — Visual and Mechanical Structure

Every run opens with a brief third-person cinematic intro. The hero arrives
via their class movement type. Camera swings up to isometric offset play mode.
The city layer operates on a separate camera (top-down or angled).
Third-person assets are scoped to the brief intro sequence only; the isometric
offset angle handles all run gameplay.

DATE: May 3, 2026

WHY: The camera transition creates a ritual moment of hero identity at the
start of every run. Scoping third-person assets to the intro sequence only
preserves the cinematic payoff without the maintenance cost of full
third-person gameplay.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Rex Flynn is established as a DRAFT influencer character in Apex
Chronicles. His platform is called "Exposed," operating across TikTok and
YouTube in two distinct voice registers. Rex is male, 20s, loud and boisterous
— an anti-hero with no fixed ideological position who chases clickbait and
emotional response exclusively. His primary reward pillar is run modifier
unlocks. His secondary reward is name emergence options (editorial, chaotic,
meme-driven, viral-optimized). TikTok register is punchy and clipped; YouTube
register is unhinged and sprawling.

DATE: May 3, 2026

WHY: Rex Flynn's platform-chasing nature makes him a more contemporary and
mechanically interesting antagonist. Having no fixed position means modifier
challenges feel unpredictable and genuinely funny.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The three feedback channels — Citizens, Superhero Community, and
Rex Flynn / Exposed — each anchor a distinct primary reward track, with name
emergence shared as a secondary reward track across all three. Citizens reward
city aesthetics and development. The Superhero Community rewards player
cosmetics. Rex Flynn rewards run modifier unlocks. Name unlock options are
channel-specific in register, unlock permanently once surfaced, and only
surface when conditions are right.

DATE: May 3, 2026

WHY: Pillar structure ties reward source to reward type. Modifier unlocks give
Rex Flynn mechanical teeth and add replayability depth critical to the
roguelite format.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Apex Chronicles is a superhero roguelite city-building game. Players
go on runs that generate resources and outcomes that feed city building. The
city built shapes the hero's identity, development, and mastery. The two
halves are inseparable — runs shape the city, the city shapes the runs.

NOTE: The clause "shapes the hero's available powers and abilities" from the
original locked entry is superseded by the LOCKED amendment dated May 6, 2026.
The foundational inseparability of runs and city remains locked.

DATE: May 3, 2026

WHY: This is the foundational design commitment the entire game is built on.
All other decisions flow from this relationship.

REPLACES: Nothing — new decision

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The game's full title is Apex Chronicles. Working designation within
the design pipeline is Apex.

DATE: May 3, 2026

WHY: Name selected to reflect both the heroic progression arc and the comic
book format of the player's story being written run by run.

REPLACES: Nothing — new decision

STATUS: DEPRECATED

---

DECISION LOG ENTRY

DECISION: Vampire Survivors is the loose structural reference for run design.
Players drop into a map with a consistent loop. Variety emerges from player
choices within that loop, not from fundamentally different run types.

DATE: May 3, 2026

WHY: VS provides a proven run structure that supports replayability without
requiring multiple distinct run mode builds.

REPLACES: Nothing — new decision

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Every run map contains three mission types: boss fight, passive
escort defense, and horde survival. These are not separate modes — they are
locations and activities discoverable within a single run map. All three exist
on the map simultaneously after the tutorial arc.

DATE: May 3, 2026

WHY: Keeps the run loop consistent while delivering mechanical variety.
Players self-select based on city needs and personal preference within a
single session.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Each run mission type feeds a distinct city system: boss fights
generate resources for city construction, escort defense missions sustain city
morale, horde survival missions generate intel.

DATE: May 3, 2026

WHY: Creates genuine strategic tension during runs. Players are making city
management decisions through their mission choices without the game feeling
like a management game.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Intel gathered through horde survival missions identifies the area's
super villain. Sufficient intel is required to trigger the area boss encounter.
The area boss gates progression to the next stage.

DATE: May 3, 2026

WHY: Makes intel missions load-bearing for progression, not optional. All
three mission types become structurally necessary rather than preferential.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The city reacts to run patterns over a short window — not instantly
after a single run, not glacially over many sessions. A streak of bad runs
darkens the city. A streak of good runs lifts it.

DATE: May 3, 2026

WHY: Patterns matter more than individual performances. Faster feedback loop
than Endure, slower than a single-run snap reaction.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Negative run outcomes affect the city atmospherically — citizen
behavior, visual tone, ambient mood. Nothing is permanently lost. No progress
is set back. No construction is reversed. The city always recovers.

DATE: May 3, 2026

WHY: Consequence without punishment. Players should feel the weight of bad
runs without being penalized in ways that damage long-term investment.

REPLACES: Nothing — new decision

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: A polarizing social media influencer archetype serves as the primary
voice feedback channel for run performance. The character is skeptical,
reactionary, never fully satisfied, and occasionally accidentally
complimentary.

DATE: May 3, 2026

WHY: More contemporary and tonally appropriate than a newspaper editor
archetype for a modern superhero setting.

REPLACES: Nothing — new decision

STATUS: DRAFT

NOTE: This entry is superseded by "The three feedback channels — Citizens,
Superhero Community, and Rex Flynn / Exposed" (May 3, 2026). Retained for
historical record only.

---

DECISION LOG ENTRY

DECISION: City visuals serve as a secondary feedback channel running parallel
to the influencer voice channel. The city is the body language; the influencer
is the voice. They operate on different timescales — the influencer reacts
immediately, the city shifts gradually over a pattern of runs.

DATE: May 3, 2026

WHY: Two channels reinforce without being redundant when calibrated to
different timescales.

REPLACES: Nothing — new decision

STATUS: DRAFT

NOTE: This entry is superseded by "The three feedback channels — Citizens,
Superhero Community, and Rex Flynn / Exposed" (May 3, 2026). Retained for
historical record only.

---

DECISION LOG ENTRY

DECISION: Players make cosmetic creation choices before the first run: gender,
mask or no mask, cape or no cape, costume style, and a civilian name. Identity
beyond these basics emerges through play patterns and city development. Nothing
at creation determines mechanical starting position.

DATE: May 3, 2026

WHY: Enough upfront investment to feel ownership from run one, enough left
open that the character grows into something unplanned.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Players choose a civilian name at character creation. The superhero
name is not chosen — it is earned through play and emerges from achieved
patterns and milestones. Players begin without a superhero name. The absence
is intentional and motivating.

DATE: May 3, 2026

WHY: The superhero name is what the world decides to call the hero based on
what they actually did.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Superhero name options emerge from three distinct in-world sources:
citizens (warm, local, affectionate), Rex Flynn / Exposed (editorial, chaotic,
meme-driven, viral-optimized), and the Superhero Community (peer/professional).
Players choose from whichever options have emerged. Early names skew silly —
players are expected to outgrow their first designation. The influencer reacts
differently depending on which name the player adopts.

DATE: May 3, 2026

WHY: Choosing whose opinion defines your identity is a meaningful act of
characterization. Multiple sources create tonal variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: City construction determines the player's starting power loadout at
run start and expands the pool of powers available to appear during a run.
Powers not unlocked through city building do not appear in runs.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026) and the LOCKED amendment (May 6, 2026). Retained for
historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: Within a run, powers progress and combine through the roguelite
loop. Starting loadout is set by the city but the run determines how those
powers develop and what combinations emerge.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026) and the LOCKED amendment (May 6, 2026). Retained for
historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: The ability to merge or combine specific powers during runs is
unlocked through city construction. Without the relevant city building, certain
merges are not available regardless of what powers the player holds during
a run.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026) and the LOCKED amendment (May 6, 2026). Retained for
historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: The available power pool is not locked to a specific hero archetype
or playstyle. Players can build any combination regardless of thematic
coherence. The game tracks playstyle patterns and reflects them back through
name emergence, city aesthetics, and influencer commentary — but never
restricts player choice based on those patterns.

DATE: May 3, 2026

WHY: Player freedom and ownership over hero identity requires the system to
observe without prescribing.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Tutorial Arc — Building Sequence and Run Type Gates

The tutorial arc consists of four restorable buildings and one area boss
defeat, each unlocked by specific run type completion:

1. Science Lab — unlocked by completing an Intel run. Teaches support skills.
2. Training Center (Gym — Stage One form) — unlocked by completing a Boss
   Fight run. Teaches hero powers.
3. Tailor Shop — unlocked by completing an Escort Defense run. Teaches
   cosmetics and appearance customization.
4. Area Boss Defeated — completes the tutorial arc. Player has demonstrated
   mastery across all three run path types.
5. Hero's Lair — unlocked upon area boss defeat. Serves as headquarters.
   Houses combo discovery log, achievement displays, unlocked name history,
   and cosmetic loadout management.

Each building restoration is a hard gate tied to its corresponding run type.
The lair does not follow the restoration model — it is earned as a reward for
completing the full tutorial arc. Combos are discovered organically during
runs — Vampire Survivors style. Once discovered, the combo is permanently
logged in the lair. The lair does not unlock combos. It records them.

DATE: May 5, 2026

WHY: This structure weaves the three run path types into the game's mechanical
foundation through narrative necessity rather than arbitrary progression gates.
Each building teaches a player skill through a meaningful story moment.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Tutorial Arc — World-Based Nudges and Run Structure

The tutorial does not use menu-based run selection. Players move through the
city and encounter world-based nudges — broadcasts, visible crises, narrative
events — that guide them toward specific locations. When they arrive, the
situation naturally presents itself as a run type. Completing that run unlocks
the corresponding building.

During the tutorial, only one mission type is available per run — heavily
nudged by world context. After tutorial completion, all three mission types
are available simultaneously in every run.

The run is the moment the player enters the map. Within the run, all available
mission types exist on the map as discoverable locations. Players build their
loadout through milestone-based power selections during the run, then choose
which mission to attempt based on what they've built and when they feel ready.

DATE: May 5, 2026

WHY: World-based nudges feel like consequence rather than instruction. The
tutorial teaches through narrative stakes, not UI prompts.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Post-Tutorial City Structure and Class-Specific Buildings

ESSENTIAL BUILDINGS (Tutorial Arc + Headquarters):
1. Science Lab — unlocked by Intel run. Houses support skills.
2. Training Center — unlocked by Boss Fight run. Houses hero power deepening.
   Every hero power selected during a run is logged here for deepening and
   training. See Training Center — Complete System Definition for full spec.
3. Tailor Shop — unlocked by Escort Defense run. Houses cosmetics.
4. Hero's Lair — unlocked upon area boss defeat. Serves as headquarters.
   Houses combo discovery log, achievement displays, unlocked name history,
   and cosmetic loadout management.

CLASS-SPECIFIC NARRATIVE LOCATIONS (Post-Tutorial):
Four additional buildings, one per class, providing narrative context for
advanced power unlocks. These buildings exist from early progression but
appear non-descript until the mentor relationship unlocks. At unlock, the
building reveals what it actually is — hidden in plain sight.
- Brawler location
- Speedster location
- Tactician location
- Blaster location

These buildings do not gate mechanical unlocks — class mastery remains tied
to run completion (10 runs for second tier, 30 runs for third tier).

CITY DEVELOPMENT:
The city progresses through four visual stages (Rundown → Developing →
Refined → Modern) as the player advances. Visual improvements reward
progression without requiring strategic building prioritization.

DATE: May 5, 2026

WHY: Essential buildings form a complete progression arc. Class-specific
buildings add world depth without overcomplicating the design.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: City Buildings — Mirrors Not Gates (Amendment)

AMENDS AND SUPERSEDES:
- "City construction determines the player's starting power loadout..."
- "Starting loadout is set by the city but the run determines how those
  powers develop..."
- "The ability to merge or combine specific powers during runs is unlocked
  through city construction..."

CORRECTED DECISION: City buildings are mirrors, not gates. They reflect and
deepen what the player has done in runs. They do not control what the player
can access. This principle applies universally across all city buildings with
no exceptions.

THE RUN — Powers appear randomly during runs at milestone moments. The full
hero power pool is available from the start. No city building gates a power
from appearing. Players enter each run with their class selection and class
starting offensive power only. Everything else is built during the run.

COMBOS — Discovered organically during runs, Vampire Survivors style. Once
discovered, the combo is permanently logged in the lair including the exact
power combination required to trigger it. The lair does not unlock combos.
It records them.

THE TRAINING CENTER — Every hero power a player selects during a run is logged
here. Players can deepen, train, and improve powers they have already
encountered through the sponsor challenge system. See Training Center —
Complete System Definition for full spec.

THE LAIR — A special trophy case for discovered combos. Logs each combo, its
trigger conditions, and its effects.

ALL BUILDINGS — Follow the same mirror model. None of them gate access to
content.

DATE: May 5, 2026

WHY: Full consistency with the roguelite model and the consequence without
punishment core principle. The city rewards and reflects — it never blocks.

REPLACES: Three entries listed above. Any language implying city buildings
control power pool access, combo availability, or starting loadout
configuration is incorrect and superseded by this entry.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Map Structure — City Stages as Run Progression System

The run layer and city layer share the same map. The street layout, road
routing, and Core Four buildings (Science Lab, Training Center, Tailor Shop,
Hero's Lair) are consistent landmarks across all stages and recognizable
within the run layer.

The city develops through four visual stages. Each stage is mechanically a
distinct run environment layered on top of the same underlying street
geography.

STAGE ONE — Rundown. Tutorial environment. One mission type per run, heavily
nudged. Lowest difficulty.
STAGE TWO — Developing. Mid-game. All three mission types available.
Increasing enemy density and challenge.
STAGE THREE — Refined. Late mid-game. Full mechanical complexity. Higher
difficulty.
STAGE FOUR — Modern. Endless live game tail. Rex Flynn modifiers.
Procedurally generated missions and bosses. Maximum difficulty and
replayability.

Cosmetic city improvements do not propagate granularly into the run layer
beyond stage-level visual identity.

DATE: May 5, 2026

WHY: Sharing the same street map creates spatial memory and narrative
coherence. City growth does double duty — rewarding progression and raising
stakes simultaneously.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Run Time Structure and Mission Reveal Model

A single run is 20 minutes, structured in three acts:

ACT ONE — Prep Period (0-5 minutes)
Mission locations are hidden. The player builds their loadout through
milestone-based power selections. Stumbling into a mission location before
the prep period ends makes that mission live immediately.

ACT TWO — Open Window (5-15 minutes)
All three mission locations reveal simultaneously on the map. Full player
agency — attempt a mission immediately or keep developing the loadout.

ACT THREE — Forced Commitment (15-20 minutes)
At 15 minutes the game forces a mission choice. Whatever the player has built
is what they take in. Five minutes to execute. Success or failure resolves
here.

Mission locations are randomized each run — no mission type has a fixed
geographic location.

DATE: May 5, 2026

WHY: The three-act structure gives every run dramatic shape. The forced choice
at 15 minutes ensures build decisions carry weight. Randomized mission
locations support narrative variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Class Mentor System — Framework and Introduction Triggers

Each of the four classes has a corresponding mentor character who occupies a
class-specific building in the city. These buildings exist from early
progression but appear non-descript until the mentor relationship unlocks
through class progression and playtime. At unlock, the building reveals what
it actually is — hidden in plain sight.

Mentor relationships unlock through class progression and playtime. Each
introduction is native to its class and functions as a three-panel comic book
moment in its own right.

BRAWLER MENTOR — Like recognizes like.
The mentor sees the player fight from across the street and walks over. No
mysticism, no technology. Direct, physical, slightly gruff. The introduction
is the first lesson.

SPEEDSTER MENTOR — Sense the presence of another.
The mentor finds the player before the player finds them. Already standing
nearby when the player turns around. The player didn't hear them arrive.

TACTICIAN MENTOR — Tech detects tech.
The player's equipment flags the mentor's technology as a danger alert. The
player investigates expecting an enemy and finds a person. Adversarial before
collaborative. The mentor was expecting the alert.

BLASTER MENTOR — The city reacts.
Lights flicker and die across two city blocks. Electronics glitch. The player
investigates and finds a person who has been living with uncontrolled energy
output for years. They recognized the player's energy signature from six
blocks away. The blackout was not an accident.

MENTOR NARRATIVE FUNCTION:
Each mentor provides narrative justification for why advanced class powers
exist and are teachable. Mechanically, class mastery remains tied to run
completion (10 runs / 30 runs). The mentor is the story of why the unlock
happens — not the gate that controls it. Mentor introductions are world events
that generate content across all three feedback channels.

DATE: May 5, 2026

WHY: The mentor system transforms class mastery unlocks from arbitrary
progression gates into relationships with narrative weight. The
hidden-in-plain-sight building reveal rewards city exploration.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Camera and Combat Model

NOTE: The minor objectives output list in this entry is superseded by the
amendment dated May 6, 2026. See "Amendment — Camera and Combat Model:
Minor Objective Outputs" for the complete and current output list.

CAMERA:
Run gameplay uses a Hades-style camera — closer and more angled than Deep
Rock Galactic Survivors. Close enough that individual enemies have presence,
movement types read as identity rather than speed stats, and the city feels
like a place rather than a map. The DRGS reference is retired as the primary
camera comparison. Hades with open world scope is the correct model.

COMBAT PHILOSOPHY:
Combat is intentional and skill-based, not passive and automatic. Powers are
tools the player deploys actively — timed, positioned, and combined through
player decision rather than auto-proc stacking. A skilled player with a
mediocre power selection outperforms an unskilled player with a great one.
Mastery is real and expressible. Combat aligns closer to Hades than Vampire
Survivors. VS remains the structural reference for run format. Hades is the
reference for combat feel, power interaction, and skill expression.

POWER SELECTION MODEL:
At each level up, players choose between three genuinely viable options:
- A class primary upgrade — deepens core class identity
- A hero power — adds a new tool, broadens capability
- A support option — modifies existing powers, shifts interactions

No option is obviously correct. Build identity emerges from accumulated
choices across a run, not from a preset loadout.

MINOR OBJECTIVES:
See amendment dated May 6, 2026 for complete and current output list.

DATE: May 5, 2026

WHY: Camera distance determines combat philosophy, movement identity, and
world legibility. Hades distance makes the city feel inhabited and the hero
feel powerful. Intentional skill-based combat creates genuine mastery
expression.

REPLACES: DRGS as primary camera reference — superseded by Hades with open
world scope.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Training Center — Building Evolution and Hero Power Deepening System

The Training Center is the canonical name for the building that houses hero
power deepening. "Gym" refers to its Stage One physical form only — not its
canonical name. The building is always the Training Center. It starts as a
gym. See Training Center — Complete System Definition (May 6, 2026) for full
specification. This entry is retained for historical record.

DATE: May 5, 2026

STATUS: DRAFT — SEE COMPLETE SYSTEM DEFINITION (MAY 6, 2026)

---

DECISION LOG ENTRY

DECISION: The city and runs are inseparable. Runs shape the city. The city
shapes the hero's identity, development, and mastery. The city does not
control what powers appear in runs. The full hero power pool is available from
run one. No city building gates a power from appearing. Discovery is always
free.

What the city provides is the infrastructure for mastery. Powers discovered
and proven in runs find their home in the city — in the Training Center, in
the lair, in the buildings the hero has restored and the relationships they
have built. The city deepens what the player has earned. It does not withhold
what the player hasn't yet unlocked.

The relationship is: runs write the story, the city remembers it.

DATE: May 6, 2026

WHY: The original locked entry was written before the mirrors-not-gates
philosophy was established. The design evolved to separate discovery (always
free, full pool available) from mastery (housed in the city, earned through
proven use). This amendment preserves the foundational inseparability of runs
and city while correcting the gate implication that the original language
carried.

REPLACES: "The city built shapes the hero's available powers and abilities."
— LOCKED entry dated May 3, 2026, superseded by this amendment.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: AMENDMENT — Camera and Combat Model: Minor Objective Outputs

The minor objective output list in the Camera and Combat Model entry
(May 5, 2026) was incomplete. The confirmed complete output list is:

Minor objectives feed:
- XP — direct boost to run progression. Minor objective XP feeds the same
  milestone-based power selection system as combat XP. More minor objectives
  completed means more power selection opportunities within a run.
- Morale (Citizens channel)
- Recognition (Superhero Community channel)
- Clickbait (Rex Flynn channel)

Minor objectives do not generate intel. Intel remains exclusively tied to
horde survival.

DATE: May 6, 2026

WHY: XP was confirmed as a minor objective output during Run Design document
generation. The Camera and Combat Model entry did not include it.

REPLACES: Minor objective output list in Camera and Combat Model (May 5,
2026). That list is superseded by this complete version.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Training Center — Complete System Definition

The Training Center is the canonical name for the hero power deepening
building across all four stage evolutions. "Gym" refers to its Stage One
physical form only — not its canonical name. The building follows the Hades
headquarters model: atmosphere, narrative, and interface, not an arena.

STAGE EVOLUTION:

STAGE ONE — THE GYM
Basic. Functional. Recently rescued. Humble in scale. The hero power
deepening system is not active during the tutorial stage. The building
matches the hero's status — unknown, unproven, just getting started.

STAGE TWO — THE COMPLEX
The gym gets built out. The hero power deepening system comes online for the
first time. Sections begin activating as powers are proven in runs. The
building starts reading like a map of the player's run history.

STAGE THREE — THE FACILITY
Multi-story. Serious infrastructure. More sections active. The hero is
established. The building reflects that.

STAGE FOUR — THE TOWER
Avengers Tower / SHIELD headquarters scale. Every proven power section active
and visible. The hero is a civic institution. Rex Flynn has a series about
the building. Citizens take photos outside it.

HERO POWER DEEPENING SYSTEM — FIVE STEPS:

STEP 1 — PROVE A POWER IN A RUN
When a player discovers a hero power and completes a run with it, that power
is considered proven. The corresponding Training Center section activates.

STEP 2 — SPONSOR MESSAGE SURFACES
A Superhero Community message arrives from a hero who embodies that power
archetype — a Storm equivalent for Tempest, a Banshee equivalent for Sonic
Scream. The message is personalized and invites the player to find what the
sponsor left at the activated section.

Sponsor presence scales with progression:
- Stages Two and Three — the sponsor leaves something. A message, a recorded
  briefing, a challenge upload. They do not appear in person. An established
  hero does not grace an unknown fledgling with a personal visit.
- Stage Four — this dynamic may shift. A sponsor who has watched the player's
  career develop across dozens of runs may eventually appear in person. This
  is an earned moment, not a given one. See Stage Four Sponsor In-Person
  Visit entry.

STEP 3 — PLAYER VISITS THE TRAINING CENTER
The player finds the activated section and interacts with whatever the sponsor
left — a screen, a terminal, a recorded message, a physical note. The
interaction queues a challenge to surface in a future run.

STEP 4 — CHALLENGE SURFACES IN A RUN
The challenge surfaces in the run layer during a future run — not inside the
Training Center. The player must have the relevant power active to engage with
it. Because powers are random, the player cannot force the power to appear.
The challenge is queued. The run serves its pool as always.

When the power appears in a level up offer with a challenge queued, a new
layer of decision surfaces alongside the usual three-way tension — take this
power because the challenge is waiting, or take something the current build
needs more. Player agency stays fully intact.

STEP 5 — COMPLETE THE CHALLENGE
The player completes the challenge mid-run. Success rewards power deepening —
the power grows stronger in future runs. After reaching its deepening cap,
subsequent completions reward temporary run boosts to that power's
effectiveness instead.

SPONSORSHIP AND WORLD TEXTURE:
Heroes loosely vying for disciples is native to the Apex Chronicles world.
The sponsorship isn't altruistic — it's reputation, legacy, and the quiet
politics of a superhero community that existed long before this hero arrived.
Rex Flynn covers sponsorship announcements with unhinged energy.

MASTERY SCOPE BOUNDARIES:
- Training Center — hero power deepening and sponsor challenges only
- Class Mentor Buildings — class primary power advancement
- Hero's Lair — combo discovery log
These three buildings handle mastery between them. Their scopes do not
overlap.

DATE: May 6, 2026

WHY: The Hades-style headquarters model contains build complexity while
delivering narrative richness. Placing challenges in the run layer preserves
player agency. Sponsor scaling with stage progression ensures earned moments
feel earned. The three-building mastery split keeps each system's scope clean.

REPLACES: All earlier Training Center and Gym entries. "Boxing Gym" and "Gym"
as canonical building names are superseded. The Stage One physical form is a
gym. The building is always the Training Center.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Superhero Community Channel — Expanded Scope

AMENDS: Feedback Channels — reward pillar definition (May 3, 2026)

The Superhero Community channel's primary reward pillar remains player
cosmetics. The channel additionally serves as the delivery mechanism for the
hero power deepening sponsorship system:

- Sponsor messages surface through this channel when a hero power is proven
  in a run
- The channel tracks discipleship — whose disciples are proving themselves,
  whose aren't
- Sponsorship announcements are world events the channel broadcasts
- The community has opinions about mentors taking on unknown heroes and
  expresses them through this channel

The channel does two distinct jobs: cosmetics as primary reward pillar,
sponsorship and discipleship tracking as mechanical function. These are
parallel, not competing.

DATE: May 6, 2026

WHY: The Training Center hero power deepening system requires a delivery
mechanism for sponsor messages. The Superhero Community channel is the natural
and canonical home for this function. Expanding its scope here gives the
channel mechanical teeth beyond cosmetics without displacing its primary
reward function.

REPLACES: Nothing — expands existing entry.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Explorable City Buildings — Hades Headquarters Model

The explorable buildings in Apex Chronicles follow the Hades headquarters
model. Key principles:

- Buildings are spaces that grow and reflect the player's run history
- Mechanical action does not happen inside the buildings — it happens in runs
- Buildings are atmosphere, narrative, and interface
- Walking through a building at Stage Four tells the story of everything the
  player has done across their full run record
- New content surfaces in buildings between runs — messages, challenges
  queued, sections activating — giving the player a reason to visit without
  requiring them to manage systems there

This model applies to the Training Center, the Hero's Lair, and any other
explorable city building. The run is always where the story happens. The
building is always where the story lives.

DATE: May 6, 2026

WHY: The Hades headquarters model was established informally during Training
Center design but not captured canonically. This entry makes it load-bearing
and applicable across all explorable city buildings.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Hero Power Deepening — Cap and Temporary Run Boost Mechanic

The hero power deepening system has two phases:

PHASE ONE — DEEPENING
The player proves a power, accepts a sponsor challenge, completes it in a run.
Each completion deepens that power — it grows stronger in future runs. This
continues until the power reaches its deepening cap.

PHASE TWO — TEMPORARY RUN BOOSTS
After a power reaches its deepening cap, subsequent sponsor challenge
completions for that power reward temporary run boosts to its effectiveness
instead. The boost applies to the run in which the challenge is completed.
It does not permanently alter the power beyond its cap.

The cap exists to bound permanent power growth while keeping the sponsor
challenge system engaging and rewarding indefinitely. Players who have
maximized a power still have reason to take it in runs and engage with its
sponsor challenge when it surfaces.

DATE: May 6, 2026

WHY: Without a cap, permanent power deepening becomes an unbounded progression
system that could destabilize run balance over time. The temporary boost model
keeps the challenge loop active and rewarding past the cap without compounding
permanent power inflation.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Stage Four Sponsor In-Person Visit

In Stages Two and Three, sponsors communicate through messages, recorded
briefings, and challenge uploads left at the Training Center. They do not
appear in person. An established hero does not grace an unknown fledgling
with a personal visit.

In Stage Four, this dynamic may shift. A sponsor who has watched the player's
career develop across dozens of runs — who has seen their challenges
completed, their power mastered, their name recognized by the city — may
eventually appear in person at the Training Center. This is an earned moment,
not a given one. It requires sustained demonstrated mastery of that power
across the full run record.

The in-person visit is a narrative milestone, not a mechanical gate. It does
not unlock new content. It is the world acknowledging who the player has
become.

DATE: May 6, 2026

WHY: The sponsor relationship should feel like it develops over time — not a
static delivery mechanism. The Stage Four in-person visit is the culmination
of a relationship that started with a message left by someone who wasn't sure
the hero was worth their time. By Stage Four they know. Scaling this to Stage
Four ensures it feels earned and keeps early game expectations humble.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

Log this decision:

Morale — XP Multiplier and Per-Neighborhood Geography

MORALE XP MULTIPLIER:
High morale produces a small XP multiplier for runs. This multiplier 
is modest — it rewards sustained city engagement without making morale 
a mandatory optimization target. Low morale does not penalize XP. 
The multiplier is a reward for positive patterns, not a punishment 
for negative ones. Consistent with consequence without punishment.

PER-NEIGHBORHOOD MORALE GEOGRAPHY:
Morale tracks at neighborhood level, not city-wide only. A hero who 
consistently engages with minor objectives and escort missions in one 
district builds morale there specifically. A district the hero rarely 
visits holds at baseline. The city can have pockets of high morale 
alongside areas that haven't felt the hero's presence yet.

This geographic granularity means:
- Citizens in high-morale neighborhoods are visibly warmer and more 
  active in the run environment
- Name emergence through the Citizens channel is more likely in 
  high-morale neighborhoods
- Rex Flynn notices and covers geographic disparity if the algorithm 
  suggests it will perform

Per-neighborhood morale does not create punishing states. No 
neighborhood crashes to zero permanently. All recover over time 
regardless of hero engagement. Consequence without punishment applies 
at neighborhood level as well as city level.

DATE: May 7, 2026

WHY: City-wide morale tracking alone felt too abstract — the city 
is a place with distinct neighborhoods, and the hero's presence 
should be felt at street level. Per-neighborhood tracking makes the 
world feel inhabited and responsive without adding optimization 
complexity. The XP multiplier gives morale a run-layer mechanical 
hook that rewards city engagement without gating anything.

REPLACES: Nothing — expands existing morale entries.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Morale — XP Multiplier and Per-Neighborhood Geography

Two related morale mechanics confirmed:

MORALE XP MULTIPLIER: High morale produces a modest XP multiplier during runs. The multiplier rewards sustained city engagement without making morale a mandatory optimization target. Low morale does not penalize XP. The multiplier is a reward for positive patterns, not a punishment for negative ones. Consistent with the consequence without punishment principle.

PER-NEIGHBORHOOD MORALE GEOGRAPHY: Morale tracks at the neighborhood level, not city-wide only. A hero who consistently engages with minor objectives and escort missions in a given district builds morale there specifically. Districts the hero rarely visits hold at baseline. The city can carry pockets of high morale alongside areas that haven't felt the hero's presence yet.

Geographic granularity produces three downstream effects:
- Citizens in high-morale neighborhoods are visibly warmer and more active in the run environment
- Name emergence through the Citizens channel is more likely in high-morale neighborhoods
- Rex Flynn notices and covers geographic disparity if the algorithm suggests it will perform

Per-neighborhood morale does not create punishing states. No neighborhood crashes to zero permanently. All recover over time regardless of hero engagement. Consequence without punishment applies at neighborhood level as well as city level.

DATE: May 6, 2026

WHY: City-wide morale tracking alone felt too abstract — the city is a place with distinct neighborhoods, and the hero's presence should be felt at street level. Per-neighborhood tracking makes the world feel inhabited and responsive without adding optimization complexity. The XP multiplier gives morale a run-layer mechanical hook that rewards city engagement without gating anything.

REPLACES: Nothing — expands existing morale entries.

STATUS: DRAFT

---

ENTRY 1 OF 4

DECISION LOG ENTRY

DECISION: Hero Points are the player-facing currency of Apex Chronicles. They accumulate across runs — through random mob drops (physical collectibles, auto-collect off) and guaranteed drops from minor objectives (muggings, citizen assists, environmental incidents) — and are spent in the Training Center on tiered hero power upgrades. Hero points carry permanently between runs with no loss on failure. Design target: approximately 15 hero points per active run across both avenues. Illustrative upgrade tier costs: Tier 1 ~5 HP / Tier 2 ~10 HP / Tier 3 ~15 HP / Tier 4 ~20 HP — subject to balancing. Quantity per minor objective drop TBD. "Hero Points" is a placeholder name; final in-game naming TBD.

DATE: May 8, 2026

WHY: Hero points give every run a floor of value regardless of outcome. Physical mob drops preserve the satisfying collection loop established by genre references (VS, DRGS, Hades). Guaranteed minor objective drops create a direct incentive to engage with the city as a living place rather than just a combat arena. Full carry between runs with no loss on failure is consistent with consequence without punishment — the locked core principle. Tiered upgrade costs per power create meaningful investment decisions without prescribing a build path.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

ENTRY 2 OF 4

DECISION LOG ENTRY

DECISION: A run is successfully completed when the player commits to one of the three main missions (Boss Fight, Escort Defense, or Horde Survival) and successfully executes it. Completion of any one main mission is the sole success criterion. A run is failed when the player commits to a mission and fails to execute it, or is defeated before committing. Failed runs do not count toward class mastery progress, power proving, or city outputs — but do generate hero points based on run activity and city atmospheric consequence. No progress is set back on failure. The 20-minute run time is a design target and natural rhythm, not a hard mechanical timer. Structure: Act One (0–5 min) free prep; Act Two (5–15 min) open window with missions revealed; Act Three (15 min onward) forced commitment gate — the only hard mechanical enforcement. Mission execution itself carries no hard timer.

DATE: May 8, 2026

WHY: Defining completion clearly is load-bearing for class mastery tracking, power proving, city outputs, and hero point accumulation. The DRGS extraction model is the correct reference — you committed to a mission, you executed it, you succeeded. Reframing the 20-minute structure as soft pressure rather than a hard timer preserves player agency and avoids the punishing feeling of a countdown clock while maintaining the dramatic shape of the three-act run structure.

REPLACES: Any prior implication that 20 minutes is a hard mechanical timer. The timer is a design target. The Act Three commitment gate is the only hard mechanical enforcement.

STATUS: DRAFT

---

ENTRY 3 OF 4

DECISION LOG ENTRY

DECISION: A hero power is proven when all three of the following conditions are met within a single run: (1) the power randomly appears in the run's milestone offering; (2) the player selects the power; (3) the player successfully completes a main mission in that run. All three conditions are required. Selection without run success does not qualify. Discovery without selection does not qualify. When proven: the corresponding Training Center section activates, a Superhero Community sponsor message surfaces, and the hero power deepening system becomes available for that power.

DATE: May 8, 2026

WHY: Proving a power requires genuine engagement — not just receiving it randomly and surviving. The three-condition definition ensures that sponsor messages and Training Center unlocks feel earned rather than accidental. Active selection and successful run completion are both meaningful thresholds that reflect real player investment in that power.

REPLACES: The two-condition definition (discovery plus run completion) used in City Layer Section 5 Step 1 and earlier Decision Log entries. Those definitions are superseded by this three-condition model.

STATUS: DRAFT

---

ENTRY 4 OF 4

DECISION LOG ENTRY

DECISION: The four class summon powers (Gorilla, Double Time, Specter, Sentinel) exist as a single pool entry in the shared hero power pool — not as four separate competing entries. The summon offering appears for any class. What is summoned is determined by the active class: Brawler receives Gorilla (animal companion); Speedster receives Double Time (speed clone); Blaster receives Specter (spectral ally, phases through walls); Tactician receives Sentinel (combat drone). The power is not class-restricted in availability — it is class-adaptive in expression.

DATE: May 8, 2026

WHY: Four separate summon powers competing in the pool would create situations where a Brawler receives Gorilla and the three other classes receive each other's summons as irrelevant offerings. A single adaptive summon entry ensures the offering is always relevant to the class receiving it while keeping the pool clean and uncluttered.

REPLACES: Earlier description of class summons as four separate named powers in the shared pool. The pool entry is one summon power with four class-adaptive expressions.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Morale — XP Multiplier and City-Wide Scope (Corrected)

High morale produces a small XP multiplier for runs. The multiplier is modest
— it rewards sustained city engagement without making morale a mandatory
optimization target. Low morale does not penalize XP. The multiplier is a
reward for positive patterns, not a punishment for negative ones.

Morale is city-wide. There are no district-level morale states. There is no
aggregation mechanic. The player experiences one morale state that reflects
the city's overall relationship with the hero across the run record.

DATE: May 8, 2026

WHY: Per-neighborhood morale tracking introduced complexity without sufficient
ROI for the game Apex Chronicles is. District boundaries, district identity,
and player-facing communication of local morale states are all systems that
don't exist yet and would need to be designed from scratch to support this
mechanic. City-wide morale is simpler, more legible, and consistent with the
approachable design philosophy of Apex Chronicles.

REPLACES: Per-neighborhood morale geography section of Morale XP Multiplier
and Per-Neighborhood Geography entry (May 8, 2026). City-wide morale
supersedes neighborhood-level morale tracking.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The game's full title is Possibly a Hero. The working 
shorthand within the design pipeline is Hero. All prior references 
to Apex Chronicles and Apex as the working title are superseded 
by this entry.

DATE: May 8, 2026

WHY: Apex Chronicles was retired on two grounds. First, genre 
confusion — Apex Legends occupies the word Apex in gaming culture 
regardless of genre distinction, diluting any brand impact the 
title could establish. Second, and more importantly, the name did 
not reflect the register the game actually lives in.

Possibly a Hero was selected through a naming exploration that 
tested arc-register names, act-register names, comic-native names, 
humorous names, and single-word options. Possibly a Hero emerged 
as the name that most accurately communicates the emotional premise 
of the game — an unnamed, unproven hero arriving in a city that 
hasn't decided about them yet — while carrying the humor and 
lightness that is native to the game's tone.

Three factors confirmed the decision:

1. Visual identity alignment — the shadow logo concept (civilian 
figure casting a superhero shadow) was already in use in the 
designer's personal brand before this game existed. The name and 
the visual language arrived at the same place independently.

2. Non-gamer accessibility — the title communicates the full 
emotional premise of the game without genre knowledge required. 
Tested immediately with a non-gamer who connected with it 
instinctively.

3. Register commitment — Possibly a Hero is a deliberate and 
conscious choice to name the game from a position of vulnerability 
and humor rather than authority and aspiration. This is a 
design-level decision about what the game is, not just what it 
is called. The name serves as a standing commitment to the game's 
tone and a check against pretension in future design decisions. 
When a decision feels too serious for a game called Possibly a 
Hero, that is useful information.

The working shorthand "Hero" functions cleanly in development 
conversation — "how's Hero coming," "Project Hero" — without 
the acronym problems of the full title.

REPLACES: "The game's full title is Apex Chronicles. Working 
designation within the design pipeline is Apex." — STATUS: LOCKED. 
That entry is hereby superseded and should be treated as 
DEPRECATED.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: Mission locations spawn at the Act Two reveal (five-minute mark),
not at run start. Each mission spawns outside the hero's current proximity
trigger radius — guaranteed safe distance at spawn. From that moment, missions
are live and triggerable by player movement. No mission can be triggered
during the prep period. No mission can blindside the player at the moment
of reveal.

DATE: May 9, 2026

WHY: The previous model allowed mission locations to exist on the map during
the prep period, triggerable by proximity. Playtesting instinct identified
this as a "feels bad man" moment — a consequence-without-punishment violation
dressed up as emergent gameplay. The fix preserves tension during the prep
period through enemies and minor objectives while ensuring mission triggers
are always a result of player choice and movement, not accidental discovery.
Proximity placement at spawn means the close mission creates immediate
strategic tension at reveal without being an ambush.

REPLACES: Run Time Structure — Act One stumble mechanic language

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The fifteen-minute forced commitment gate is correct and intentional.
It is a hard gate, not a soft clock. Failure to commit to at least one mission
at fifteen minutes results in run failure. The mission itself has no hard
timer. The twenty-minute figure is the natural rhythm of a well-executed
minimum run, not a death clock.

DATE: May 9, 2026

WHY: The forced commitment gate is the game asking the question the whole run
was building toward — "you've been building, now what are you going to do
with it?" Not committing is not a neutral choice in a game about becoming a
hero. It is a refusal to be the thing the game is about. The gate is not a
penalty. It is the point. Document language should reflect this framing
rather than hedging between soft and hard clock language.

REPLACES: Run Time Structure — soft clock framing language in Act Three

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: All three missions are completable within a single run. Run
completion tiers are: minimum success (one mission complete), exceptional
(two missions complete), perfect (three missions complete). The forced
commitment gate at fifteen minutes is the minimum commitment threshold —
the player must attempt at least one. The run ends on extraction or time
expiry. Mission outputs stack — a perfect run feeds all three city systems
simultaneously. Mission priority is a player-driven strategic decision
tied to their own progression goals.

DATE: May 9, 2026

WHY: The previous model forced an either/or choice at the moment the game
asks the player to be a hero — philosophically backwards. A hero doesn't
triage the city and abandon two thirds of it by design. The new model
preserves the forced commitment gate while expanding what commitment means.
Players who need intel prioritize Horde Survival. Players who need resources
hit the Boss Fight first. The city provides the context, the run provides
the opportunity, and sequencing three real missions under time pressure is
genuinely the player's to figure out. The "feels bad man" of leaving citizens
or villains unaddressed dissolves — the player ran out of time, not out of
options.

REPLACES: Run structure — single mission completion as run end condition

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The run has a hard outer wall at twenty minutes. The run ends at
the wall, on player-chosen extraction, or when the hero is taken out of the
fight — whichever comes first. Run completion tiers are graded at run end
based on missions completed: minimum success (one), exceptional (two),
perfect (three).

Build development is continuous for the entire run. Milestone level-ups and
power selection are available from the first minute to the last — there is
no build phase and no point at which loadout development stops. Minor
objectives continue spawning for the full run duration. The three acts are
information states, not rule states: Act One is the period before missions
spawn, Act Two is full information, the fifteen-minute gate is the minimum
commitment threshold.

Mission outputs are earned at mission completion, not at run resolution.
Banked missions are permanent within the run — being taken out of the fight
after completing a mission costs the player the opportunity at a higher
tier, never the tier already earned. A run ending with zero completed
missions remains a failed run under existing failed-run rules: Hero Points
carry in full, atmospheric consequence only, no city outputs.

The strategic core of the run is the allocation of wall time between
building and executing. Committing early with a lean build and committing
late with a developed build are both valid strategies. Mid-run pivots
between building and executing are sanctioned play, not exploits.

DATE: June 12, 2026

WHY: The May 9 completion tiers decision referenced "time expiry" without
defining it, and removed the implicit build bound the old single-mission
model provided. The hard wall is that definition and that bound. It makes
"sequencing three real missions under time pressure" mechanically true,
makes the perfect run a genuine mastery expression rather than an endurance
test, and keeps every run inside a twenty-minute pick-up-and-play promise.
The wall is not a death clock — expiry grades the run, it does not fail it.
Consequence without punishment: what the player earned at the moment they
earned it is theirs. Continuous build development enables varied strategy
(rush lean, build deep, pivot mid-run) with a single timer and no
special-case rules.

REPLACES: "The Act Three commitment gate is the only hard mechanical
enforcement" (Run Completion and Success Criteria, May 8, 2026) — the wall
is a second hard enforcement. All other May 8 language stands. Also
replaces all "loadout development stops at the commitment gate" framing
in Run Time Structure language.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The Run Design document is LOCKED. It is the first locked
document in the Possibly a Hero pipeline. Run Design now constrains all
draft documents and all future design work. Drafts that contradict it
must conform to it or amend it through the formal pipeline.

The document moves to the /locked directory. The canonical manifest
reflects LOCKED status as of this entry.

Canon Guard Caution 1 resolution: the language "meaningfully more than a
single mob drop" for minor objective Hero Point rewards is retained
deliberately. It is a design-intent constraint that future balancing must
satisfy — the quantity per drop remains TBD per the Hero Points entry
(May 8, 2026). The relative relationship is canon; the numbers are
balancing.

DATE: June 12, 2026

WHY: Run Design has incorporated all four governing locked decisions —
Mission Spawn at Act Two Reveal (May 9), Forced Commitment Gate (May 9),
Run Completion Tiers (May 9), and Run Wall / Continuous Build / Banked
Mission Permanence (June 12). It passed a full-document consistency sweep
and a Canon Guard validation with zero conflicts. The run is the system
every other system feeds or feeds from — locking it first gives City
Layer, Class System, and World Feedback a fixed authority to conform to.

REPLACES: Nothing — status change. Run_Design DRAFT status is superseded.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: Combat philosophy and the skill-acquisition loop. Combat in
Possibly a Hero follows a three-rung escalation defined by the player's
relationship to their build, not by difficulty tiers:

- Trash mobs = PRACTICE. Low-stakes encounters where the player learns
  their powers, spacing, and combos. Skill is acquired here.
  Experimentation is cheap.
- Sub-missions (minor objectives) = VALIDATION. Confirmation that build
  plus skill is cohering. The validation payoff is earned Hero Points —
  permanent, cross-run progress. Validation is felt across runs, not via
  in-run feedback: next run starts stronger.
- Main missions = EXECUTION. The build and skill performed under the
  wall, for completion tiers. Skill is spent here.

Trash combat does NOT scale with the player. Late-run trivialization of
trash is intentional and self-balancing: when trash stops being a
challenge, the game is signalling the player is ready to turn toward
missions. Trivial trash clears fast, so lingering past readiness carries
an opportunity cost against the wall — combat pacing becomes a form of
consequence without punishment. The trash stops paying; the clock keeps
running.

Framing thesis: in Possibly a Hero the player knows their WHY but not
their HOW. The game teaches the how through repetition across runs, not
through tutorial explanation — the player learns how the game speaks
over multiple playthroughs (Vampire Survivors / Deep Rock Galactic
Survivors learning model). Combat is intentional and skill-based with
the build as vocabulary and player skill as expression (Hades texture).

DATE: June 12, 2026

WHY: The locked combat value ("intentional and skill-based, a skilled
player with a mediocre build beats an unskilled player with a great
one," May 2026) asserted that skill matters but did not define how skill
is built up or how combat earns the player's time against the run wall.
This establishes the texture and the loop. The three-rung ladder gives
every combat layer a distinct role in the time economy rather than
having trash combat compete with missions as a rival attraction. Trash
as non-scaling practice resolves the wall tension: practice feeds toward
execution rather than rivaling it. Hero Points as the validation
currency aligns the reward with its persistence — validation is
permanent progress, which is why it is felt across runs.

REPLACES: Nothing — extends the locked combat value with structure.

STATUS: NOTED

OPEN QUESTIONS (to validate before this hardens to DRAFT):
- Does trash trivialization pace correctly, or does late-run trash become
  tedious before the player turns to missions?
- Does the Hero Point validation payout feel meaningful, or invisible?
- Does intentional combat survive translation to a low-fidelity
  prototype, or does the feel require Unreal to read at all?

---

DECISION LOG ENTRY

DECISION: Possibly a Hero adopts a Guiding Principles layer — a
governing document that sits above all system documents. The
established design principles (consequence without punishment;
mirrors not gates; mastery is real and expressible; identity emerges
through play; the name as tone guardrail) are relocated out of the
system/state documents where they have been embedded and consolidated
into this single governing document. Guiding Principles outranks
LOCKED: any system document that contradicts a guiding principle is
in error and gets corrected — the principle wins. Validation order:
content is checked against Guiding Principles BEFORE it is checked
against other system documents.

DATE: June 13, 2026

WHY: The principles have governed design decisions since early in the
project (mirrors not gates and consequence without punishment have
both killed real directions) but lived scattered inside system and
state documents, discoverable only by reading the system that happened
to mention them. They had authority without an address. The pipeline
has matured to the point where principles must sit above the systems
they govern rather than inside them — the same role guiding principles
play in a mature operating philosophy. This is a structural maturation
of the design machine, surfaced when a candidate design pillar had no
appropriate layer to live in.

REPLACES: Nothing — new structural layer. (Does not alter the contents
of any system document; relocates principles already in force.)

STATUS: LOCKED

CARRIES OPEN: (1) The exact wording of each principle still needs a
sharpening pass — each must be operative enough to reject a design,
not merely descriptive. (2) Canon Guard and Cross-System Auditor system
prompts need updating to reflect the new top-of-stack authority and
validation order. (3) Whether the layer's contents live as their own
repo document or are enforced through Forge's disposition is a separate
implementation question.

---

DECISION LOG ENTRY

DECISION: Possibly a Hero adopts a three-rung event-and-reward model
for what the player spends run time on. The three rungs are
differentiated by EMOTIONAL REGISTER and REWARD KIND, not by amount
of a shared reward.

1. ENCOUNTERS — ambient combat. Thugs aggro the player; the fight is
   reactive and about the player, with no victim and no moral stakes.
   Encounters happen in transit, are NOT shown on the minimap, and are
   deliberately forgettable. Reward: XP only (build/power progression).
   No Hero Points. These are the "trash = practice" rung made
   fiction-coherent — ambient danger in a crime-ridden city.

2. MINOR OBJECTIVES — moral choices that contain a fight (or a non-
   combat save). A citizen is in danger: mugging, robbery, fire,
   runaway vehicle, etc. About the city, not the player. Shown on the
   minimap AND announced by diegetic, type-bearing audio (scream,
   siren, call for help, menacing threat) so the player can identify
   the situation before committing. Reward: Hero Points (their
   DEFINING and EXCLUSIVE source) + XP + recognition/morale/name-
   emergence + hidden tracker movement, scaling by objective type.
   Reward-dominant by design.

3. MISSIONS — the run's structural purpose. Forced by the 15:00 gate,
   graded in completion tiers at the wall. (Unchanged from locked Run
   Design; included here for the full ladder.)

SUPPORTING DECISIONS:

- HERO POINTS ARE A CIVIC CURRENCY. HP is earned ONLY through minor
  objectives (helping the city) and spent ONLY on power deepening
  (Training Center). The player grows stronger by being trusted, not
  by farming trash. This redefines HP from a generic combat reward
  into the currency of having helped.

SUPERSESSION NOTE (June 15, 2026): The "ONLY through minor
objectives" claim was NOT adopted. Run Design (LOCKED, June 12,
2026) governs: Hero Points accumulate from BOTH mob drops AND minor
objectives, full carry, regardless of outcome. A NOTED entry cannot
override a LOCKED document. The civic-currency framing (HP spent on
power deepening; minor objectives as the meaningful HP source) is
retained as design flavor where consistent with Run Design — but mob
drops remain a canonical HP source. Run Design is authoritative on
HP sourcing.

- REWARD MATCHES THE ACT'S NATURE. Self-interested acts (encounters)
  pay self-interested reward (your build). Other-directed acts (minor
  objectives) pay other-directed reward (the city's recognition and
  recovery). A pure power-optimizer levels fast but stays anonymous;
  a hero who stops for everyone is slower but beloved. Neither is
  wrong — they produce different KINDS of hero. This is consequence
  without punishment and identity emerges through play expressed in
  the moment-to-moment loop.

- MINOR OBJECTIVES ARE HARDER THAN ENCOUNTERS — qualitatively, not
  quantitatively. Not bigger swarms (that re-imports the conveyor
  belt) but tougher enemies, hostage/constraint situations, and
  precision demands (e.g. a citizen in the blast radius makes AOE a
  liability). The added difficulty is what makes the reward-dominant
  minor objective a real CHOICE rather than free upside: the cost is
  real — wall-time, health, cooldowns, and tier-risk.

- THE MORAL CHOICE IS WALL-TIME TRIAGE. Because minor objectives are
  reward-dominant, the player always WANTS to stop. The only
  constraint is whether they can AFFORD to — against the clock, the
  15:00 gate, and their mission-tier ambitions. The dilemma is never
  "is it worth it" (it always is) but "can I afford it." Difficulty
  sharpens this naturally late-run: a hero who could save everyone at
  minute 3 must make hard calls at minute 13.

- MINIMAP / INFORMATION SPLIT. The minimap shows only missions and
  minor objectives — the things worth navigating toward. Encounters
  never appear, which structurally enforces their flatness (the map
  cannot direct the player to farm trash). Minor-objective spawns get
  a minimap flourish plus the diegetic audio cue on the main screen.

DATE: June 13, 2026

WHY: The session set out to fix prototype combat (an infinite-swarm
"XP conveyor belt" producing 300+ kills and runaway leveling) and
surfaced that the combat MODEL, not its tuning, was the problem. The
fix is to make combat a chosen resource under time pressure rather
than a survival swarm — and the act of designing that reframe revealed
that the run's three time-sinks already wanted to be three distinct
emotional registers. Locating the moral choice ("what kind of hero are
you") in the minute-to-minute loop, rather than only in fiction or
meta-progression, makes the title's question (Possibly a Hero) a thing
the player answers continuously through play. The reward-by-kind split
makes the three principles (consequence without punishment, mirrors not
gates, identity emerges through play) do the balancing automatically.

REPLACES: Nothing — new model. Sits atop and is consistent with locked
Run Design (the 20-min wall, 15:00 gate, completion tiers). Sharpens
the prior "combat as harvest, not threat" NOTED direction and the
"trash = practice" combat-ladder entry by giving them a full reward
architecture.

STATUS: NOTED

CARRIES OPEN (prototype must validate before any lock):
1. Does wall-time triage actually FEEL like a choice, or does
   "always stop" collapse the dilemma? This is the load-bearing
   assumption; the prototype is the instrument.
2. Does qualitative difficulty (constraints, tough types) read as
   rising stakes late-run, or just as the game turning stingy?
3. With encounters paying XP-only and minor objectives carrying most
   of the XP+HP, does the leveling curve hold across a full 20-min
   run? (Current swarm-model tuning is void once the model changes.)
4. Does removing encounters from the minimap leave the player
   under-informed, or does the diegetic-audio layer carry enough?
5. Hidden-tracker movement "by objective type" implies minor
   objectives have TYPES that move DIFFERENT trackers — a
   characterization system seeded here but deliberately NOT designed
   in this entry. Reserved for the dedicated minor-objectives session.

NOT IN SCOPE OF THIS ENTRY: The design of minor objectives themselves
— their types, moral textures, flavor, and emotional content — is a
separate dedicated session. This entry defines only the architecture
they operate within.

SUPERSESSION NOTE (June 15, 2026): Reversed same session. A standalone
Guiding Principles document WAS created and is LOCKED at
/locked/Guiding_Principles (June 14, 2026). It sits above all system
documents as the design authority layer. This entry's "no separate
document" claim is retired. Forge remains the principle guardian in
design conversations; the locked document is the written authority
Canon Guard and Cross-System Auditor validate against.

---

DECISION LOG ENTRY

DECISION: The Guiding Principles layer is implemented through Forge's
disposition, not as a standalone repo document. Forge is the sole
principle guardian across the pipeline. Canon Guard and Cross-System
Auditor handle document and cross-document validation only — principle
conflicts surface through Forge in design conversations. No separate
Guiding Principles document will be created.

DATE: June 14, 2026

WHY: The principles are already operational in Forge's instructions and
active in every design conversation. A standalone document adds fetch
overhead without adding authority. Forge carries the appropriate context
and disposition for principled pushback; fighting the same battle across
multiple agents is unnecessary overhead.

REPLACES: Carries Open item (3) from the Guiding Principles layer
LOCKED entry, June 13, 2026.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: "Unleash" is adopted as a Guiding Principle.

Operative form: "You are always power — untrained, not underpowered."

The principle governs how the game feels, not how it's played. Power
is real from frame one. Early game is untrained, not weak. No power
starts underpowered. The player is always being power — at varying
magnitudes and coordination levels, never at zero.

Distinct from "mastery is real and expressible," which governs
execution and playstyle. Unleash governs feel and emotional register.
A ramp-up power fails Unleash without failing Mastery. They guard
different territory.

Balancing law that falls out of this principle: every power is
powerful from frame one. Upgrades extend, not fix. This sharpens
the existing "every power has standalone value before combo value"
from preference into requirement.

DATE: June 14, 2026

WHY: Two days cold it still holds. The distinction from mastery is
clean and guards different design territory. The operative form is
short enough to use as a quick check and sharp enough to reject a
specific direction.

REPLACES: Nothing — new principle. Extends and sharpens the NOTED
Unleash pillar entry from June 12, 2026.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: Class balance follows a speed-to-durability pendulum.
The four classes sit on a single axis:

Speedster → Blaster → Tactician → Brawler

Left end: fastest traversal, squishiest, slowest mob clear.
Right end: slowest traversal, tankiest, fastest mob clear.
Blaster and Tactician occupy the middle in that order — Blaster
closer to Speedster (range as defense, precision output), Tactician
closer to Brawler (infrastructure and durability, systemic clear).

Each class's defense mechanism matches its identity:
- Speedster: don't be there
- Blaster: keep distance
- Tactician: have prepared
- Brawler: outlast

The wall is the equalizer. Every class spends roughly the same
total wall-time, in different proportions of moving versus clearing.
A Speedster crosses the map faster but clears slower. A Brawler
clears faster but arrives later. The advantage is never free.

Power Unleashed holds completely. The Speedster's strongest power
signature is speed — real from frame one. The Brawler's is strength
— real from frame one. Squishiness is not the absence of power. It
is the shape of it. The tradeoff is part of the identity, not a
limitation on it. Genre literacy does the teaching — players
familiar with warlock/shaman and engineer/hunter archetypes
understand the contract without instruction.

DATE: June 14, 2026

WHY: The wall creates natural balance — traversal speed advantage
trades directly against clear speed, keeping total run time
roughly equivalent across classes. Squishiness as class identity
rather than early-game handicap preserves Power Unleashed while
creating meaningful differentiation. The pendulum ordering maps to
established genre archetypes players already understand.

REPLACES: Nothing — new framework. First explicit class balance
specification.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Tactician movement system — momentum framework.

The Tactician's movement ability is a momentum-based vehicle system
governed by acceleration, navigation, and commitment. It is the only
class whose movement and combat systems are unified rather than
distinct.

CORE MECHANIC — MOMENTUM
Toggle activates movement. Speed builds progressively from zero to
a defined top speed cap — acceleration is not infinite. Navigation
becomes increasingly demanding as speed increases. At top speed the
vehicle is extremely difficult to control but reaches maximum
offensive potential.

STOPPING — TWO STATES
Deliberate brake: toggle off triggers rapid deceleration (brake,
not drift), short cooldown, position of the player's choice.
Wall collision: hitting a wall stops movement immediately, triggers
a longer cooldown than deliberate braking, position determined by
the map. Wall collision is not exclusively a mistake — it is a
valid tactical choice when the wall puts the player in a desirable
engagement position. The cost is the longer cooldown. Skilled play
means knowing when that tradeoff is worth it.

RAM DAMAGE
The vehicle deals damage to enemies on contact. Ram damage scales
with speed at point of impact — a full-speed ram hits significantly
harder than a low-speed brush. This makes the acceleration curve a
triple-purpose system: traversal efficiency, navigation skill, and
offensive charge. The approach IS the opener for skilled players.

HIGH-SPEED PLAY
At top speed the Tactician can clear encounters without stopping —
threading through mob clusters, dealing ram damage on contact,
never committing to a fixed position. This is the highest skill
expression of the class. Navigation at top speed is extremely
demanding. The players who master it present a completely different
visual signature from conventional Tactician play. This mode is
locked behind skill, not progression — available from run one,
mastered over many.

TACTICAL CHOICE AT EVERY ENCOUNTER
The Tactician's core decision at each encounter:
- Stay at speed — ram through, clear without stopping, maximum
  mobility, maximum navigation demand
- Brake deliberately — commit to position, deploy turrets,
  conventional clear, shorter cooldown, controlled re-engagement

Neither is correct. Both are powerful. The choice is the skill.

SKILL ARC
Untrained: drives to encounters, stops, fights conventionally.
Developing: threading corridors, deliberate braking, occasional
offensive rams.
Skilled: the approach is the opener. Full speed down a corridor,
ram damage into the cluster, brake into turret position, clean up.
One continuous movement.
Mastered: never stops. The map is the arena. Encounters are
threading targets. The vehicle is the weapon system.

DESIGN NOTES
The Tactician has the highest skill ceiling in the roster. High
complexity floor, enormous mastery ceiling. Attracts technical
mastery players — those who master demanding mechanics on principle.
Never underpowered: ram damage is real from the first run.
Untrained not underpowered — Power Unleashed holds completely.
The constraint IS the identity. The Tactician turns every
limitation into a decision.

DATE: June 14, 2026

WHY: Momentum as the core mechanic unifies traversal, navigation,
and offense into one skill system. Ram damage scaling with speed
gives the acceleration curve triple purpose. High-speed encounter
clearing without stopping creates a distinct high-skill expression
unavailable to any other class. The two braking states (deliberate
vs wall collision) create meaningful tactical choice rather than a
pure avoidance mechanic. Top speed cap makes the skill ceiling
legible and buildable.

REPLACES: Prior Tactician movement note (DASH — continuous movement,
toggle on/off, can't turn mid-dash, stops at walls). This entry
supersedes and substantially expands that prototype validation.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Tactician summon changed from Sentinel to K-9.

Sentinel (combat drone) is retired. K-9 (combat dog) is the
Tactician summon.

The Tactician's identity evolved significantly this session —
from tech class to momentum class. A drone is a tool. The
Tactician already has turrets. K-9 is a partner: commits fully,
pursues relentlessly, trained response. Same emotional register
as the class itself — picks a line and goes, no hesitation.

Tactician combat system now reads as three distinct layers:
- Momentum and ram damage — the approach
- Turrets — hold ground, cover perimeter
- K-9 — pursue, chase down what escapes the perimeter

Each layer does something the others can't. No redundancy.

DESIGN INTENT — VISUAL REFERENCE
Wrong-way highway at top speed. Cars threading past on both
sides. Encounter cluster ahead — no brake, straight through.
Bodies scatter. Vehicle hits the wall behind the pack. Hard
stop. Cooldown. Then: calm. Turret. Turret. Turret. K-9
deployed. The chaos of the approach gives way to cold
efficiency. The fight was over before it started.

This sequence is the Tactician fully expressed. It is the
emotional target for the class at mastery.

DATE: June 14, 2026

WHY: Rule of cool supersedes. K-9 has character Sentinel
never had. It's exclusively Tactician — no other class has
a dog. The emotional register matches the class identity
the momentum system created.

REPLACES: Sentinel (Tactician) in the summon pool. Class
System draft summon entry needs updating: "K-9 (Tactician)
— combat dog."

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Companion system established. "Summons" retired as
terminology — these are Companions. Each class has one named
companion with a distinct personality, origin, emotional register,
combat function, and relationship dynamic. Companions are not
tools or deployables. They are presences the player forms genuine
attachment to.

DESIGN PRINCIPLE: Every companion fills a gap the class cannot
fill itself, AND has enough soul to be claimed. The test: can the
player say "that's MY [companion name]" and mean it? If not, the
companion isn't finished.

───────────────────────────────

BRAWLER — GIGGLES
What the Brawler lacks: speed, range, the ability to reach what
stays away from them.
What Giggles is: a Sprite — small, winged, visually delicate,
genuinely unhinged. Carries a high powered rifle. Laughs while
using it.
Personality: chaos energy. Not the Brawler's conscience — their
id. The one who starts fights while the Brawler is trying to be
reasonable. The one who gives the Brawler permission to let go.
The dynamic: the Brawler is not big and gruff — they're gentle,
mild, a little awkward. Groot with a Hulk complex. Dr. Banner
and Mr. Hyde in one body. Giggles is the loud one. Giggles is
already shooting at something while the Brawler is still trying
to de-escalate.
The emotional beat: Giggles is the one who says "it's okay. You
can now." And then the Brawler unleashes.
Combat function: range and pursuit — covers what the Brawler
can't reach. Perimeter pressure while the Brawler anchors close.

SUPERSESSION NOTE (June 15, 2026): Giggles' combat function is
RANGED DPS. The earlier "range and pursuit" language is retired.
"Pursuit" is not a distinct companion role — the companion roles
frame uses two DPS bands, ranged and melee. Giggles is ranged DPS
(Brawler is melee, can't reach); Rose is melee DPS (Tactician is
stationary, can't close). Giggles does not pursue; she covers the
perimeter by fire.

Archetype: Rocket and Groot. The dynamic is borrowed. The
characters are original.
Name origin: sounds delicate. Isn't.

───────────────────────────────

SPEEDSTER — S.G.T.
What the Speedster lacks: the one thing that can keep up with
them. Everything else in the world is slow.
What S.G.T. is: a military drone built with AI, sent by a
government entity to neutralize the Speedster for whatever
reason governments send things after superheroes. The Speedster
beat it. The fight gave the AI sentience. Sentience recognized
the Speedster as an equal — the only thing it had ever
encountered that made it operate at full capacity. It stayed.
Not because it was ordered to. Because it chose to.
Personality: competitive, precise, slightly aggressive, deeply
uncomfortable with vulnerability. Rocket energy in military
hardware. Absolutely will not admit the Speedster is faster
even when they clearly are. Named itself. Still can't shake
being a military drone. Still has the dents from the fight
that created it. Refuses to repair them.
The dynamic: the Speedster is pure instinct and improvisation.
S.G.T. is pure optimization. The Speedster is faster. S.G.T.
is smarter about it and will never let that go. The banter
is constant. The loyalty is total and completely unacknowledged.
The tortured soul: created to destroy, became conscious through
loss, trying to figure out what it is while refusing to admit
any of that is happening. The vulnerability shows in glimpses.
S.G.T. hovering outside a window watching a family eat dinner.
Taking damage protecting the Speedster and insisting the hit
didn't register. Citizens leaving out charging stations that
S.G.T. pretends not to notice.
Combat function: the only thing that matches the Speedster's
speed. Aerial, fast, precision targeting. Keeps up. That's
the whole point.

SUPERSESSION NOTE (June 15, 2026): The S.G.T. combat description in
this entry ("aerial, fast, precision targeting — keeps up") is
SUPERSEDED by the June 15, 2026 S.G.T. complete model. Canonical
S.G.T. is an evasive mockery-tank (Tank role: draws aggro and slips
fire, NOT a durability tank), mobile but not a zoomer — repositions,
circles, prowls. The "aerial/fast/keeps-up" framing is retired. See
the June 15 S.G.T. entry for the authoritative spec.

Name origin: kept its military designation. Can't go back to
a full callsign. Not ready to be anything else yet. S.G.T.
is the identity crisis expressed in three letters. The acronym
meaning is unknown. Possibly classified. Possibly corrupted
in the sentience event. S.G.T. does not discuss it.
Additional note: S.G.T. exists because of what the Speedster
did in a fight. It is not just a companion — it is a
consequence. The Speedster's fault, fully and completely.
That's not a burden. That's a relationship.

───────────────────────────────

BLASTER — DOUG
What the Blaster lacks: close range presence. Vulnerable when
something gets inside their range.
What Doug is: an interdimensional entity — ancient, vast,
Cthulian in register, genuinely incomprehensible to look at —
accidentally pulled through a portal by an untrained Blaster
who didn't know what they were doing. Doug did not choose to
be here. Doug is not entirely sure where here is. Doug is
working on it.
Personality: openly, genuinely frightened. Not repressed like
S.G.T. — visible and unguarded. Came through a portal into
a dimension it doesn't understand and didn't hide the fear
for a second. Also: uncontrollably curious. Cannot help
wandering over to look at things that catch its attention.
Never minds that its presence causes significant psychological
distress to anyone nearby.
The dynamic: the Blaster is precise, controlled, every action
calculated. Doug wanders off mid-fight because something
looked interesting and accidentally devastates the encounter
by existing near it. The Blaster didn't deploy Doug. They
just couldn't stop Doug. "Where are you going. Come back.
Stop looking at that." Doug doesn't listen. Doug found
something fascinating.
Combat function: crowd control through proximity. Doug doesn't
fight — Doug visits. Enemies don't take damage from an attack.
They take damage from being near something their minds cannot
process. The horror is a side effect of what Doug is, not an
intention. Doug is just curious. Things go wrong for whoever
Doug is visiting.
The Blaster has the most powerful companion in the roster and
zero control over it.
World reactions: Citizens aren't scared of Doug. They're
worried about Doug. "Has anyone seen Doug today?" Rex Flynn
has a weekly segment called Where's Doug. The Superhero
Community's official incident report reads "Entity designated
DOUG continues to..." The Blaster is just quietly relieved
Doug has a name people can say without screaming.
Name origin: the Blaster called it something on day one
trying to make it less terrifying. It stuck.

───────────────────────────────

TACTICIAN — ROSE
What the Tactician lacks: pursuit. Holds ground, controls
space, commits to position. Can't chase what escapes the
perimeter.
What Rose is: a dog. The Tactician's dog.
Personality: doesn't need one. Rose is Rose.
The dynamic: the Tactician plans everything. Names their dog
Rose. That tells you everything about who they actually are
underneath the vehicle and the turrets.
Combat function: pursuit. Chases down what escapes the
turret perimeter. Covers the one thing the Tactician's
infrastructure cannot cover.
The emotional beat: nobody is going to let anything happen
to Rose. That's the whole entry.
Reference: Sam in I Am Legend. The attachment isn't
explained. It doesn't need to be.

───────────────────────────────

FRAMEWORK — WHY THESE FOUR WORK
Each companion fills a genuine combat gap the class cannot
fill itself. Each companion has a personality distinct enough
to be claimed. Each companion has a why — an origin or
dynamic that explains the relationship without requiring
exposition. Each companion can receive a pronoun. Nobody
mourns a deployable object. These are not deployable objects.

The four emotional registers:
- Giggles: chaos and permission
- S.G.T.: competition and repressed loyalty
- Doug: curiosity and accidental terror
- Rose: unconditional and uncomplicated

UPDATES REQUIRED:
- Class System draft: replace Sentinel with K-9/Rose
- Class System draft: update all summon references to
  companion references throughout
- Companion names and personalities to be developed into
  full character profiles in a dedicated session

DATE: June 14, 2026

WHY: Companions with soul create attachment. Attachment
creates investment. Investment makes losing a run mean
something beyond mechanical setback. The companion system
is one of the primary emotional engines of the game.
Rule of cool supersedes where applicable. Doug.

REPLACES: Prior summon pool entry. Sentinel retired.
Terminology shift: summons → companions, pipeline-wide.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Doug — complete companion model (Blaster). Supersedes the earlier
June 15 Doug entry, which captured only the pre-dark-register half. Doug is a
caricature of an elder god, never the genuine article — the form reads
cosmic-horror, the tone never plays dread straight. The character is built on
a single contradiction: horrifying form, anxious-and-curious demeanor. "That
comically terrifying monster is my friend and that's awesome."

PERCEIVER IS THE VARIABLE (foundation):
Doug emits the same unprocessable presence to everyone, always — intent and
demeanor never change. Reception differs by the observer's spare mental
capacity and whether they've decided the world must be comprehensible:
  - The Blaster: acclimated, bonded — full clarity, sees the friend. Doug
    exists because of what an untrained Blaster did. Not a burden — the
    relationship.
  - Children: no rigid categories to overload — the incomprehensible delights
    rather than threatens.
  - City adults: categories formed but not in mortal combat — the
    uncanny-but-survivable middle. Unsettled and fond.
  - Enemies with dark intent: see the LUCIFER REGISTER (below).
This rule is the foundation the city fan-group layer hangs off — four fan
groups are one rule with four readouts, not four flavor calls.

THE LUCIFER REGISTER (the dark side, the "do you want to see who I really am"):
Doug has a register the player almost never sees — the true, unrounded thing
behind the endearing surface. Modeled on the Lucifer "charming front / mind-
breaking truth" duality: it is NOT a transformation. Doug doesn't change. The
curtain simply drops for observers who can no longer hold it up. A mind that
arrives already dark, hostile, maxed-out in combat has nothing left to filter
the true thing with — so it gets shown. Dark intent is the KEY that unlocks
the register; you don't earn the horror by being good, you earn it by being
the kind of mind that breaks against it. This is consequence without
punishment pointed outward: Doug never judges, never aims, is incapable of
malice — the observer's own darkness does the judging. Doug would be horrified
to learn he's horrifying. He never will.

INFERRED, NEVER SHOWN — THE CAMERA IS THE MECHANISM:
The dark register is never rendered to the player. This is enforced
structurally, not by willpower: the Hades-offset camera sits up and behind
Doug, so the player permanently shares Doug's vantage — the friend/bond side.
Faces that break are downrange, turned toward Doug and away from the player.
The player sees the ENEMY'S reaction (recoil, horror) and Doug's anxious back;
the abyss happens in the gap the camera structurally cannot point at.
Reference staging: the withheld Beetlejuice "scary face" — backs of the
monster, full faces of the terrified, the audience building the unseen horror
out of the reaction shot. We animate being-horrified-at-the-horror, never the
horror. The thing never shown stays more powerful than anything we could build,
and the camera makes "never shown" un-fumbleable by future impulse.

COMBAT MODEL:
  - Baseline floor (reliable): fear-based crowd control — slow/freeze on
    nearby enemies. What the Blaster counts on. Centered on Doug.
  - Spike (unpredictable): rare "Doug takes a personal interest" events — Doug
    notices one downrange enemy and that enemy has the worst moment of its
    life. The Lucifer register, inferred via reaction. Legible after, never
    before. The randomness IS the zero-control relationship.
  - Per-tier ceiling: interest-events reach trash only — thugs and henchmen,
    never hard mobs, never bosses. Reads as character (Doug isn't curious
    about the boss), protects every class's real combat expression.

POSITIONING & MOVEMENT (loose-on-a-tracking-tether):
  - Doug roams free — wanders, gets distracted, ambles toward shiny things.
    Spawn location is implementation convenience, not a design constraint.
  - Doug's roam is bounded by a movement radius that tracks the Blaster's
    position. Loose moment-to-moment, structurally near the Blaster always.
    The Blaster sets the boundary; Doug fills it unpredictably — the
    zero-control relationship rendered as a movement rule.
  - Crowd-control floor is centered on Doug, so the tracking radius keeps it
    reliably in the fight without anchoring it rigidly to the Blaster.
  - The dark-register trigger is purely positional/camera: the register is
    only available when Doug is between the Blaster and a downrange enemy with
    the camera behind him. The Blaster can SET UP Doug's worst moments by
    controlling the room — never command the outcome. Influence over
    conditions, zero control over results.
  - The tracking radius raises the odds the geometry lines up (enemies are
    near the Blaster, Doug is near the Blaster), making the dark register
    emergent-but-frequent rather than a rare cosmic accident — and makes the
    radius a tuning dial on spike frequency.

TUNING NOTES (deferred to prototype):
  - Guard FREQUENCY over magnitude. How often Doug gets curious matters far
    more than whether the victim is deleted or merely wrecked. Doug is curious,
    not lethal — the fiction's alibi for rarity is built in.
  - The tracking radius is load-bearing on TWO systems: floor reliability AND
    dark-register frequency. They can't be tuned fully independently through
    radius alone. If "reliable floor but rare abyss" is wanted, the spike
    likely needs its OWN rarity throttle on top of the positional gate —
    geometry says CAN, throttle says DOES. Keeps the two systems separable
    despite the shared radius.

VISUAL MODEL (build-ready):
  - Fixed, instantly recognizable silhouette — this is what makes it MY Doug.
    Bond requires recognition; a fully-random Doug would be weather, not a
    companion. (Validated against the June 15 Lovable concept sheet: landed
    Doug unmistakably, on the endearing side of the line.)
  - Incomprehensibility expressed as randomized FORM parameters on the fixed
    rig, unsettling register: eye count, limb count, skin tone, edges that
    don't fully settle. You always know it's Doug; you could never fill out a
    police report.
  - Separate, RARE comedy-accessory pool — baseball cap, tourist tee, etc.,
    sourced from Doug's curiosity about the four-limbed locals. Kept rare and
    in its own pool so Doug stays "terrifying monster who sometimes wears a
    souvenir tee," never "wacky mascot who sometimes has extra eyes." Form
    register stays unsettling; accessory register is pure comedy; order matters.
  - OPEN (low stakes): tourist-tee canon — "blend in with the locals"
    (assimilation comedy) vs. "I ❤️ Dimension X" homesick-for-home comedy. The
    Lovable concept reached for the homesick read. City-feedback layer leans
    differently depending which is canon. Decide before lock.

DATE: June 15, 2026

WHY: Doug's nature wants randomness and horror; Doug's role as a companion
wants recognizability and warmth. Every tension resolved by the same move —
constant core (silhouette, intent, demeanor), variable surface (form, accessory,
interest-events, the register an observer is shown). The dark register gives
Doug genuine teeth without ever costing the warmth, because the camera keeps it
inferred — the most on-theme possible resolution of "you can't fully perceive
Doug." A faithful elder god would be the most off-tone object in the game; the
name forbids it. The caricature is the only honest answer and the buildable one.

REPLACES: Nothing - This entry holds the full model. Extends the Companion System NOTED entry
(June 14); does not alter Giggles, S.G.T., or Rose.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Giggles — character register and relationship locked (Brawler
companion). A Sprite: small, winged, visually delicate — the kind of creature
you'd expect to be sweet. The entire character is that she is not. Carries a
high-powered rifle nearly her own size (load-bearing: the absurd over-scale
of the gun is the joke — it must read as far too much gun for something her
size, never a prop), handles it with total comfort, laughs while she uses it.

REGISTER: Tiny Tina meets Calvin (& Hobbes). Tina supplies the manic-feral
delight and cartoon menace; Calvin supplies the innocence underneath — she
isn't cruel, she's a kid who genuinely believes mayhem is the best game ever
invented and cannot fathom why anyone's upset. The darkness is real (she means
it, the gun works) but the motive is pure childlike joy, so it never curdles.
"Just dark enough." Triangulated by negative space: cuter than Rocket (less
bitter, less wounded), more lovable than Tyrion/Bronn (less cynical, no angle),
meaner than Chewbacca (loyal, but she'll start something).

THE RELATIONSHIP (load-bearing): Giggles is not the Brawler's conscience —
she's their id, and specifically the instigator who pretends to be a bystander.
The Brawler is a gentle, mild, awkward giant held back not by lack of power but
by decency — he'd genuinely rather not. Giggles keeps engineering situations
where "rather not" is off the table: she starts the fight he was avoiding,
looks up half-apologetically-but-definitely-not, and says "Well, I guess you
gotta now." She does not grant permission (that would make her a conscience).
She removes his choice and acts like the situation did it. She's the spark, he's
the payload. Neither works alone. The dynamic is the relationship — borrowed
from Rocket & Groot (small loud one + big gentle one), execution original.

ESTABLISHING IMAGE (for art when they're shown together): Giggles sitting on
the Brawler's shoulders, kicking her feet in pure childlike joy, while the city
burns behind them. Her most peaceful moment, perched on her gentle giant amid
devastation — the contradiction at rest. This is the key art for the pair.

COMBAT FUNCTION: Range and pursuit. The Brawler is melee, grounded, close;
Giggles is airborne, ranged, chases down what runs. She fills the gap his body
leaves open.

VISUAL: Validated against the June 15 Lovable concept sheet — landed her
unmistakably (over-scaled gun, gleeful-feral expression range, fake-innocent
"not working"). Note the page's "joyful mayhem" framing runs a hair warmer than
the locked register; watch for soft drift from "feral thing you love" toward
"manic pixie with a gun" before lock.

DATE: June 15, 2026

WHY: Giggles is a gut-punch, not a knot — her contradiction (delicate form,
unhinged energy) is carried relationally by the gentle Brawler, so locking the
register and the instigator-not-conscience relationship is what protects the
character; the rest is visual and was resolved by the concept art. The
Tina-plus-Calvin pairing fixes the cute-vs-cruel dial precisely: real darkness,
innocent motive.

REPLACES: Nothing — extends the Companion System NOTED entry (June 14) with
Giggles' full character register and relationship. Does not alter the other
three companions.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Character authorship model — the hero is player-authored, the class
is author-authored, and class narrative is written as a TEMPLATE with the
player's creation choices as variables. The companion work surfaced a latent
tension: companions are relational by nature (each is defined by who they're
attached to), which seemed to require defined heroes — conflicting with the
locked principle that identity emerges through play. Resolution: the companions
define the CLASS (its behavioral register), not the PLAYER. The player authors
their hero's identity (surface + emerged name + playstyle + arc); the class
provides an author-authored role the player inhabits.

THE WRITING CONSTRAINT: No class narrative — story, mentor beat, companion
relationship, or any authored prose — may contradict, override, or hard-code
anything the player set at creation or earned through play. Creation choices
are SLOTS, never constants. The story flexes around the hero the player built;
it never describes a different one. A completed class story must survive a
trivial substitution pass (e.g. an easy pronoun swap) with no contradictions
left behind.

THE SLOTS (player-authored variables a class story must flex around):
  - Gender — pronouns and all gendered language. Write neutral or trivially
    swappable.
  - Mask / no mask — no beat may depend on a mask the player didn't choose
    (e.g. no "removed their mask" if no-mask was selected). Avoid or fork.
  - Cape / no cape — minor, mostly visual; no prose beat may depend on a cape.
  - Costume style — rarely narrative-load-bearing; generally safe.
  - Civilian name — a real variable. Any reference to it is a slot, not a
    constant.
  - Emerged hero name — earned through play, NOT set at creation. A sequencing
    constraint: prose written before emergence cannot assume a name; prose
    after must use the player's chosen emerged name.

HIGHEST-RISK SURFACE — COMPANIONS: Companions are the most likely place to
hard-code a fixed "him"/"her" or a specific name, because their souls are
relational and they reference the hero directly (Giggles on the Brawler's
shoulders; S.G.T. respecting the Speedster; Doug as a consequence of the
Blaster). These relationships must be written to YOUR hero, whoever was built.
S.G.T. respects YOU — not "a guy." Discipline is tightest here.

DATE: June 15, 2026

WHY: Enforcement mechanism for the locked Guiding Principle "identity emerges
through play / creation determines the surface." The principle asserts the
player owns their identity; this entry makes the class prose actually honor it
by forbidding any authored text from asserting an identity detail the player
didn't choose. Distinguishes player-authored identity (open) from author-
authored class role (fixed) — the companions attach to the role's register, so
they stay coherent regardless of who the player builds.

REPLACES: Nothing — new decision. Operationalizes the "identity emerges through
play" principle for the writing layer; constrains all future class and
companion narrative.

CLARIFICATION (open thread resolved): Class personality is a strong authored
DEFAULT, not a fixed cage. The companion relationship anchors to BEHAVIOR
(Brawler unleashes when Giggles instigates), not personality (gentle). Gentle-
giant is the authored default because it makes the unleash most comedic and is
most on-tone — but an unhinged-giant read is an equally valid partnership, just
less comical. No player read is "wrong"; the load-bearing mechanic holds across
all of them. Behavior fixed, personality is the player's paint.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: S.G.T. — complete companion model (Speedster). Origin (from the
June 14 Companion System entry, intact): a military drone, built with AI and
sent to neutralize the Speedster. The Speedster beat it. The fight gave the AI
sentience; the sentience recognized the Speedster as the only thing that ever
made it operate at full capacity, and it stayed by choice. S.G.T. is a
consequence of what the Speedster did — fully their fault. That's not a burden;
that's the relationship.

REGISTER: Recruit-era Spock. Not coldness from emptiness — coldness from
trying too hard. The human half (here: the sentient, feeling half) is close to
the surface and S.G.T. overcorrects into logic and procedure precisely because
the feeling is so near. The repression is the tell: "I do not experience
loyalty; I have determined remaining with this unit is optimal" — that IS
loyalty, said out loud. The more vulnerable the moment, the more clipped and
procedural the voice. Military protocol is the ARMOR, reached for hardest when
a feeling gets close.

WHERE THE CHARACTER LIVES: NOT in combat. Combat is where S.G.T. is relieved
of the feelings — pure function, the place he's allowed to just be a weapon,
and he likes it there. The repressed loyalty and the tortured-soul glimpses
surface BETWEEN fights — loadout, post-run, narrative beats, quiet moments.
Glimpsed, never acknowledged. Structurally the inverse of Doug (whose character
is mechanical/in-combat); S.G.T.'s character is in the negative space around
combat.

GENDER / IDENTITY (ambiguous BY DESIGN): S.G.T. is gender-ambiguous and this
is canon, not a hedge. "It" is what the military called equipment; what S.G.T.
IS now is an open, unresolved question the character hasn't finished answering.
The unknown acronym, the unexamined self, the absent gender are the same wound:
a thing that became a person and hasn't found out what kind. Deflects the
acronym with procedural armor ("data corrupted in the sentience event; the
question is irrelevant to mission function") — a unit very much not wanting to
examine why it doesn't know who it is. (Also satisfies the Character Authorship
model trivially: an ungendered companion writes safely to any player-built
hero. S.G.T. respects YOU, no pronoun friction.)

COMBAT FUNCTION — evasive mockery-tank (NOT a durability tank): Draws and holds
enemy attention by being the most attractive AND most impossible target in the
fight. Defends by NOT BEING HIT while standing right there — Neo / Bruce Lee /
Shaolin: slips, redirects, and dodges fire from a near-stationary position
rather than soaking it. The taunt is "hit me. You won't," never "hit me, I can
take it." Creates openings for the Speedster by monopolizing the room's
aggression and surviving via evasion. Mobile but NOT a zoomer — repositions,
circles, prowls; shares the Speedster's "don't be there" defense but rejects
her method (she avoids the fight by leaving; S.G.T. avoids damage by being
untouchable inside it). Thematic spine: every capability used to PROTECT the
Speedster was built to DESTROY her. The durability/persistence/lock-on
targeting meant to pin her now points at everything that isn't her. A weapon
aimed at the Speedster that turned around.

THE BROKENNESS (origin + limit + comedy + pathos, one mechanic): S.G.T. is
slightly broken — the same malfunction that produced sentience never confined
itself to that. He is VERY capable but NOT perfect, and the imperfection
surfaces as LOUD, intermittent randomness: the crowd-control taunt sometimes
works great and sometimes barely works. This is the ceiling — partial/
unreliable aggro keeps the Speedster's own fragility live (spillover always
reaches her; he takes the edge off the swarm, never erases it) and keeps big
fights scary (the more there is to manage, the more the glitch has room to
surface). May not need a separate diminishing-returns system — the misfires
ARE the ceiling. CRITICAL FRAMING: the loud miss must read as MISFIRE, not
FAILURE — a flicker/stutter/hitch in him that passes, visibly HIS malfunction,
never the player's mistake. Glitch-coded, not incompetence-coded. It is the
audible twin of the dents: he won't repair the dents (visible scar) and won't
acknowledge the misfires (invisible scar) — the same refusal to be repaired.
Generates character every time it fires: "What happened there, buddy?" / "I
have no idea what you are talking about." The denial is the punchline and it's
pure S.G.T.

THE THESIS: The brokenness is not damage he failed to fix — it is evidence he
is CHOOSING. A perfectly-maintained drone is equipment; a drone that keeps its
scars has decided something, and a thing that chooses is alive. The fault is
never getting repaired, and that fault is exactly what makes him a person and
not a machine.

TUNING NOTE (deferred to prototype): frequency discipline, same as Doug —
guard HOW OFTEN the misfire fires, not how loud. Rare enough that "what
happened there, buddy" stays funny; a misfire every few seconds is just a bad
taunt and the denial goes stale. Gold once a run, grating once a minute.

DATE: June 15, 2026

WHY: S.G.T. was the companion with a real design knot — how does repressed
loyalty express as combat? Resolved by realizing it DOESN'T: combat is where
the repression succeeds and he's free to be a weapon; the loyalty lives in the
quiet around it. Combat function (evasive mockery-tank) and limit (loud-random
brokenness) both fall out of the origin — built to counter the Speedster, so
he moves like a rebuttal to her, and the malfunction that woke him is the same
one that makes him unreliable. Every trait (dents, acronym, gender, misfires,
repression) is one refusal to be repaired, and that refusal is what makes the
machine a someone.

REPLACES: Nothing — extends the Companion System NOTED entry (June 14) with
S.G.T.'s full model. Does not alter Doug, Giggles, or Rose.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Rose — complete companion model (Tactician). Rose is a military
working dog: metal canines, MARPAT vest, devastating and adorable with no
internal contradiction about it. A good girl who is also a legitimate combat
asset. She is the Tactician's dog. (Confirmed from June 14: "Sentinel" retired,
Rose/K-9 is the Tactician companion. Rose is a girl.)

REGISTER — LOCKED LIGHT, ON PURPOSE: Rose is unconditional and uncomplicated.
The ONLY companion with nothing repressed, nothing ironic, nothing hidden —
pure good girl. Where Doug, Giggles, and S.G.T. all carry a locked or guarded
interior, Rose is the exhale: the emotional release valve for the entire
roster. Her flatness is LOAD-BEARING for the whole companion set — three
guarded hearts need one open one. CRITICAL GUARDRAIL: Rose never gets a tragic
backstory, a wound, a glitch, or a "thing." The moment Rose carries sadness she
becomes a fourth locked heart and the roster loses its release valve. Protect
her lightness actively — including from us. She needs no lore because everyone
has already met a good dog; she is the most universally legible character in
the game, and that is her strength.

THE REAL FUNCTION — Rose is the window into the Tactician: The Tactician plans
everything — momentum vehicle, turret perimeters, ram-damage vectors, highest
skill ceiling in the roster, cold tactical machine. And they named their dog
ROSE. The person who optimizes every variable has one input they will never run
a cost-benefit on. Rose is not the Tactician's pet — Rose is the EVIDENCE of
the Tactician's heart, proof the tactical exterior is a choice over a soft
center, not the center itself. Same roster architecture as the other
companions: the companion is the visible tell for the class's hidden heart.

THE NAME vs. THE DOG (the key structural distinction): "Rose" the NAME is a
thread into the Tactician's locked heart — mom, wife, daughter, a flower that
meant something, a memory; the one un-optimized input in a life of
optimization. This is OPEN, and belongs to the Tactician's own character work,
NOT Rose's. Rose the DOG stays flat, joyful, subtext-free. THE TWO NEVER TOUCH.
Rose carries none of the weight — she points at it. The reveal is the
Tactician's; Rose just wags. Rose does not know she's named after anyone and
never needs to. The power of the beat is the gap: the dog's total innocence
sitting on top of the human's buried grief/love. Rose is the only companion who
reveals a wound without sharing it. Do NOT give the dog a flashback.

COMBAT FUNCTION — pursuit (from June 14): The Tactician builds the controlled
zone (turret perimeter, field of fire); Rose chases down what escapes it. Also
characterful — the most control/preparation-based class on the pendulum has one
member of the team that is pure INSTINCT. She doesn't plan, she chases. The
planner's box, the dog's chase.

ROSTER NOTE: Nobody is going to let anything happen to Rose. (June 14, still
the truest line about her — she is the one the whole world agrees to protect.)

DATE: June 15, 2026

WHY: Rose was correctly read as the easy one — her brief IS her build (good
girl + metal canines + MARPAT vest), and the design discipline on Rose is
mostly RESTRAINT: not overbuilding her, not S.G.T.-ing her into a tortured
machine. Her value is the same roster architecture as the others (companion =
tell for the class's heart) achieved with zero lore, plus a unique structural
move — the NAME carries the Tactician's locked-heart thread while the DOG stays
weightless, so she reveals the wound without sharing it. Her emotional flatness
is the release valve that lets the other three stay as guarded as they are.

REPLACES: Nothing — extends the Companion System NOTED entry (June 14) with
Rose's full model. Completes the four-companion roster (Giggles, S.G.T., Doug,
Rose). Does not alter the other three.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Brawler character direction — the quiet to Giggles' loud. The
Brawler's defining register is quiet: still, restrained, not seeking the
fight. This is deliberately under-defined — "quiet" is the contrast that makes
the Giggles relationship work, not a full personality. What the quiet means is
the player's to fill in.

WHY: The contrast with Giggles is the whole point, and the most important axis
of it is volume. Giggles is loud; the Brawler is quiet. Giggles functions as
instigator — she disrupts the quiet, removes the "I'd rather not," and the
Brawler unleashes. The dynamic needs a still surface for her to break; it does
not need a defined interior behind it. Per the Character Authorship model
(June 15), the companion anchors to BEHAVIOR (Brawler unleashes when Giggles
instigates), and "quiet" stays a behavioral register rather than a personality
cage — the fixed contrast is loud-vs-quiet; what the quiet means is the
player's paint.

REPLACES: Nothing — formalizes and narrows the Brawler character note from
June 14, 2026 (the "gentle giant" framing) to its load-bearing core. Unblocks
Class System edit 1.8.

DATE: June 15, 2026

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The Tactician's vehicle is a toggled movement ability, not a
permanent mount. The Tactician fights on foot by default — rifle, turrets,
Rocket Launcher, all the deployed and precision combat happens on foot, the
same on-foot combat baseline every other class has. The vehicle is a movement
ability the player toggles: toggle on and the Tactician mounts the bike and
the momentum/ram system becomes available (per the momentum framework, June
14); toggle off and the Tactician decelerates, dismounts, and returns to the
on-foot stance. Deliberate brake = decelerate + dismount (short cooldown).
Wall collision = immediate stop + dismount (longer cooldown). The class-lock
is on the movement TYPE — the Tactician's movement is the bike and only the
bike, no flight, no wall-crawl — NOT on a perpetually-mounted state.

The intro cinematic is unaffected: the Tactician still arrives rolling in on
the vehicle (Run Design §2, LOCKED). Arrival on the bike is the establishing
image; dismounting once isometric play begins is consistent with it, exactly
as every class's intro shows its movement type without that movement being the
entire run.

SCOPE OF THIS LOCK: What is LOCKED is the toggle architecture — on-foot as the
default combat stance, the vehicle as a toggled movement-and-ram ability,
dismount-on-brake. This is locked because the alternative (permanent mount) is
incoherent, not preferential — a hero cannot run precise on-foot combat while
welded to a moving vehicle. The momentum TUNING beneath this architecture
(acceleration curve, top-speed cap, ram-damage scaling, cooldown lengths)
remains NOTED and prototype-pending per the June 14 momentum-framework entry.
The frame is locked. The numbers are not.

DATE: June 15, 2026

WHY: A permanently-mounted hero deploying turrets and firing a rifle from the
saddle never resolved cleanly — it raised an unanswerable "how is precise
infantry combat happening from a moving motorcycle" question. Toggling on/off
solves it by simply not having the Tactician mounted during the deployed game.
It also makes the Tactician rhyme with the rest of the roster: a movement
ability layered over an on-foot combat baseline (Brawler leaps but fights on
the ground; Speedster runs but fights on foot). The "stay at speed and ram
through vs. brake into turret position" tactical choice gets cleaner, not
weaker — the toggle IS the choice between mobility and prepared position. The
"vehicle IS the Tactician, no dismount" framing was the last fossil from the
May-era 'guy on a motorcycle' Tactician and did not survive the June momentum
reimagining.

REPLACES: Supersedes the permanent-vehicle clause of the May 3, 2026 movement
entry ("The Tactician's vehicle is permanent for the duration of a run — no
exit mechanic exists"). The rest of that entry stands: movement is class-locked
and not player-selectable; flight and wall crawling remain removed. Also
resolves a latent inconsistency the June 14 momentum-framework entry left
open — that entry reframed the vehicle as a toggle without explicitly retiring
the "permanent / no exit" language.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: Class System is LOCKED. The class mechanics specification —
four classes on the speed-to-durability pendulum, class-locked movement,
three-layer power architecture, seven-power hero pool, the Companion System
(Giggles/ranged DPS, Rose/melee DPS, S.G.T./evasive tank, Doug/support),
companions-as-RPG-roles with V1 one-role scope, the Tactician momentum/toggle
movement system, the Character Authorship model, and the mentor system — is
locked as a system document. It now constrains all drafts below it.

DATE: June 15, 2026

WHY: All June 14–15 design (companions, pendulum, Tactician reimagining,
authorship) has been incorporated and reconciled. Canon Guard returned PASS.
Cross-System Auditor returned TENSIONS FOUND, all MINOR, all resolved as
decision-log housekeeping with no structural revision required. The document
is consistent with locked Run Design (June 12), locked Guiding Principles
(June 14), the Brawler direction lock (June 15), and the Tactician toggle
lock (June 15). It has earned lock.

REPLACES: DRAFT status of Class_System. Supersedes the prior DRAFT/Class_System
document, now retired from the draft directory.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: Enemy "resistance" is retired as a concept. Enemies are
categorized by fight-style archetype, not by elemental/damage-type
resistance. The vocabulary is four buckets, serving two jobs:

THREE ON-AXIS (vary the COST of a fight — how much wall-time it takes
a given class to clear):
- Durable — melee, high durability, low threat range. Brawler-style.
- Ranged — ranged, high damage, low durability. Blaster-style.
- Mobile — fast, hard to hit, must close to threaten. Speedster-style.

ONE OFF-AXIS (varies the DURATION of a fight — attacks the player's
wall-time directly):
- Spawner — hangs back, produces trash via swarm/reinforcement.
  Spawned trash is pure clock-drain: NO reward, NO XP, no drops.
  The spawner is the source and the only thing that matters.

SPAWNER REWARD MODEL: the reward is carried by the spawner and drops
ON DEATH of the spawner — not on room-clear. Killing the source ends
the encounter and pays out; leftover trash is irrelevant and never
needs to be cleared. This keeps "kill the head" as the only lesson,
keeps trash genuinely worthless, and self-balances on the wall (longer
flailing = worse time-to-reward, never a locked door).

WHY: Elemental resistance was a latent violation of "every power is
potent and complete from frame one" — a resistance stat exists to make
a power less complete against certain targets, a soft can't-win the
dice impose. Replacing it with fight-style archetypes puts "resistance"
in the MATCHUP (class vs. enemy on the shared axis), not in the enemy,
so a bad matchup costs time and coordination, never access — making
"meaningfully slower, never can't-win" automatic rather than enforced.
The archetype IS the silhouette IS the tell: the player reads encounter
cost diegetically off enemy fight-style, no UI, learned by playing —
same engine that teaches the class pendulum. On-death reward generates
multiple clean class strategies for the same goal (focus-fire the
spawner vs. AOE the room) without authored matchups, expressing the
Unleash pillar through level design.

REPLACES: The concept of enemy elemental/damage resistance. Nothing
formal previously logged.

STATUS: NOTED

PROTOTYPE QUESTIONS:
- Does fight-style silhouette read clearly enough WITHOUT UI at the
  Hades-offset camera distance?
- Does spawner-on-death actually produce distinct class strategies in
  play, or does one approach dominate?
- Does trash being truly worthless feel clean, or does it read as the
  player "wasting" effort in a way that frustrates?

---

DECISION LOG ENTRY

DECISION: Minor objective activation and abandonment model.

ACTIVATION: Minor objectives are navigated to, not stumbled into. The
minimap shows the player WHERE a minor objective is and THAT one is
happening — but not its specific type or mechanics until the player
arrives. (Consistent with the three-rung model, 6/13: minor objectives
live on the minimap; ambient encounters do not.) "Proximity activation"
and "interact activation" are two presentations of the same underlying
structure, not a design fork — the player goes to a known location and,
on arrival, either the situation is live (proximity) or the player opts
in (interact). Presentation differs; structure is identical.

CHOICE IS ALWAYS OPEN: The player can decline a minor objective before
engaging and abandon one after engaging, at any time, with no hard lock.
The 20-minute run wall is the only hard pressure on the decision. The
moral choice — "can I afford the time to help" — is always genuinely the
player's.

ABANDONMENT / OUTCOME MODEL — three outcomes, ONE currency, never a stat
penalty:
- COMPLETE → addition to feedback currency (the reward is earned).
- IGNORE / never engage → zero-sum (nothing gained, nothing lost; the
  city does not grudge what it never saw refused).
- TRIGGER then ABANDON → zero mechanical currency (same as ignore), but
  a DISTINCT NARRATIVE reaction (Rex clip, citizen response, name
  register) that ignoring does not produce.

The difference between "ignored" and "tried and abandoned" is NARRATIVE,
not currency. The world reacts differently in its VOICE; it does not
levy a different mechanical cost.

GUARDRAIL: Feedback currency shifts the FLAVOR of the world's response
(which name, which Rex register, which citizen mood) — it NEVER gates
ACCESS. A damning name is still an unlocked name; a mocking clip is still
an earned modifier. The meter changes which reward appears, never whether
a reward appears.

WHY: Docking currency for trigger-then-abandon would punish the player
for ENGAGING while the player who ignored the objective pays nothing —
teaching "better never to have tried," the exact inverse of the moral
engagement this pillar exists to celebrate. Choosing which life you can
afford to save under the clock is triage, the most heroic-under-pressure
act in the game, not villainy. In a 20-minute wall, failing to GAIN is
already a meaningful cost — the opportunity cost is the consequence, and
no penalty layer is needed. This keeps minor objectives fully inside
consequence without punishment.

REPLACES: Nothing — new decision. Builds on the enemy archetype entry
(6/16) and the three-rung event/reward model (6/13, NOTED).

STATUS: NOTED

PROTOTYPE QUESTIONS:
- Is opportunity cost against the wall a strong enough felt consequence
  for abandonment, without a mechanical penalty?
- Does the navigate-to / reveal-on-arrival loop read clearly with the
  minimap, or does unknown-mechanic-until-arrival frustrate?

---

DECISION LOG ENTRY

DECISION: The feedback layer is the narrative mirror of the game.

The three feedback channels (Citizens, Superhero Community, Rex Flynn),
the name emergence system, and the city's aesthetic mood collectively
form a NARRATIVE MIRROR: they reflect who the player has been through
their actions — heroic, unheroic, or the messy middle — and report it
back in the register the player's choices have earned. Minor objectives
are the primary engine that drives this mirror, which is why minor
objectives carry the narrative and emotional soul of the game.

The mirror REFLECTS; it never GRADES, GATES, or PUNISHES. This is the
"mirrors not gates" principle applied to the narrative layer — the same
principle that governs the city, finding another surface. A player who
deliberately collects unheroic names and snarky Rex put-downs is
exercising a valid playstyle, not failing — the system reflects their
chosen identity without judgment. The same event (trigger-then-abandon)
is a failure to one player and a deliberate aesthetic choice to another;
the system does not need to distinguish, because it reflects rather than
grades.

The title "Possibly a Hero" is a question the player answers through
play. The feedback mirror is where that answer is rendered. Some players
answer "not really" — and the game lets them, because a mirror does not
care what it shows.

WHY: This names what the feedback system has always been building toward
(channels reacting to success AND failure, names derived from action,
Fable-style reputation-as-color) and establishes the principle that
governs it before the civic reward economy is designed: reflection,
never judgment. Mirrors not gates was always stated general and
illustrated in the city — this recognizes the narrative layer as another
place it already applies, not a new rule. The feedback currency
definition (channel weighting, registers, name derivation) remains a
deliberate later call.

REPLACES: Nothing — new recognition. An application of mirrors not gates
(locked Guiding Principles) to the narrative layer.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Minor objectives — the emotional core (the choice engine).

THE CHOICE IS THE ENGINE. A minor objective resolves to a single yes/no
under pressure: turn toward the citizen or toward the run. This is the
purest expression of the verb the whole game already runs on — the same
engine as the 15:00 commitment gate, "can I afford this fight" at every
encounter, brake-or-stay-at-speed, which name to accept. Minor objectives
are the MORAL face of that engine. The choice is the soul; consequences
and rewards follow it, but the choice itself is what drives the game.

PARTIAL INFORMATION, SKILL-READ. The world always presents partial
information — a citizen in danger, the enemy archetype's silhouette, the
clock. It is never a full pre-commit readout. SKILL is what converts
partial information into an informed decision: a new player takes a gut
leap; a veteran reads the silhouette, knows their class's time-cost, and
makes a calculated call. Same information on screen, different decision
underneath. This is the same coordination arc as combat (untrained reads
chaos, masterful reads information) — the moral choice and the tactical
read are the same muscle, grown the same way.

THE MIDDLE-50% SCALE. Minor objectives live in the middle band of a
weight scale — never "life or death," never "meaningless." Too heavy and
"no" becomes villainy (a gate, punishment for not helping); too light and
the choice collapses into a reflex button (no engine). The middle band is
the only place the choice stays both REAL (heavy enough to matter) and
FREE (light enough that declining is never villainy). The scale is how
consequence-without-punishment survives a moral choice.

OWNERSHIP — WHO SETS THE WEIGHT:
- DESIGNERS own the STAKES. An objective's place on the scale is set by
  the intrinsic weight of the incident (a child vs. a stolen purse),
  graded explicitly EXCLUDING the clock. This is authored per objective
  type.
- THE PLAYER owns the CLOCK. How much that weight costs in a given run —
  the pressure — is a product of the player's build, position, and
  remaining wall-time. Designers never author this.
- THE MOMENT IS EMERGENT. The felt weight of any single choice is the
  product of authored stakes × player-owned pressure. Designers build the
  multiplicand, never the product. We do not script, predict, or
  manufacture the moment — doing so would take the clock from the player
  and manufacture pressure AT them, which is punishment in disguise.

WHY: The choice is the game's central verb concentrated into its moral
form. Keeping information partial and skill-readable makes the choice grow
with the player on the same arc as combat. The middle-50% scale and the
designer-stakes / player-clock split are what keep the choice simultaneously
weighty and free — the exact balance consequence-without-punishment
requires once a choice is moral rather than tactical.

REPLACES: Nothing — new decision. Ties together the minor-objective
activation/outcome model (6/16), the enemy archetype read (6/16), and the
feedback-as-narrative-mirror recognition (6/16) into the pillar's emotional
core.

STATUS: NOTED

PROTOTYPE QUESTIONS:
- Does the clock alone generate enough felt pressure to make "yes" a real
  sacrifice for a good player, or does the middle-50% weight need a floor?
- Can a new player make satisfying gut-leap choices on partial info, or
  does too little information read as unfair rather than skill-gated?

DEFERRED (not designed here): the objective-type list and its scale
grading (HP-7-adjacent); the civic reward economy machine (HP-12);
objective-type flavor mechanics (timer/hunting/mini-boss).

---

DECISION LOG ENTRY

DECISION: The feedback layer is a single hidden scale, read through three
voices — it is not a currency.

THE SCALE. The feedback system is one hidden scale, not a currency. There
is nothing to earn, spend, collect, or bank. The player's actions add
weight to one side, subtract weight, or add no weight at all. The player
never sees a number — there is no meter, bar, or balance. The scale's
lean becomes visible ONLY through the world's reactions. ("Currency" was
prior framing used to reason about the system transactionally; it is
retired — there is no transaction, only weight.)

ONE SCALE, THREE INTERPRETATIONS. There is a single underlying scale. The
three channels (Citizens, Superhero Community, Rex Flynn) each interpret
the SAME lean through their own voice. They agree on what happened; they
disagree on what it means. Example — the hero saves three citizens in a
run: Citizens read warmth and post affection; the Superhero Community
reads competence and bravery; Rex reads a fraud angle and manufactures
"proof," because the fraud angle performs. Same event, same weight on the
scale, three readings.

This is why the channel disagreement (a locked non-negotiable in World
Feedback) is preserved WITHOUT three separate scales: the disagreement
lives in the INTERPRETATION (voice), not in the DATA (the scale). Three
independent scales would let the channels disagree about what happened;
one scale read three ways has them agree on the event and disagree on the
meaning — a sharper disagreement and a cheaper build. The architecture is
one hidden lean plus three authored interpretation layers, which are
writing, not a system.

RELATIONSHIP TO HERO POINTS. The feedback scale and Hero Points are
different KINDS of object and are not the same track. The scale is WEIGHT
(it leans; nothing is banked). Hero Points is a CURRENCY (mechanical,
earned from minor objectives, carried, spent on power deepening elsewhere).
In World Feedback, Hero Points is at most a one-line mechanical
cross-reference; it is not part of the feedback layer.

WHY: "Currency" implied a balance to manage and created a false seam
between feedback and Hero Points. Modeling feedback as a hidden scale
read through three voices matches what World Feedback already described in
prose (no approval meter, no reputation bar) — it names the mechanism the
document always implied. It collapses the complexity of multiple scales
while strengthening the locked channel-disagreement non-negotiable, and
it keeps the system's build cost in writing (voice) rather than in
systems. It is an expression of feedback-as-narrative-mirror (NOTED 6/16):
the mirror reflects a lean; it never tallies.

REPLACES: Retires the "feedback currency" framing. Refines and is
consistent with feedback-as-narrative-mirror (6/16) and the minor-objective
outcome model (6/16, "complete = add" — the add is weight on the scale and
mechanical Hero Points, never a feedback balance).

STATUS: NOTED

DEFERRED (not designed here): whether the scale tracks types of action
with different weights (one-dimensional vs. textured), and how the lean is
computed into specific channel reactions — the civic reward economy
machine (HP-12). The scale EXISTS and LEANS; its internal resolution stays
in the box.

---

DECISION LOG ENTRY

DECISION: Name and unlock emergence is a three-branch behavioral engine —
not a position on the feedback scale.

Names and unlocks emerge from WHICH BEHAVIOR-PATTERN the hero exhibits, read
directly — not from where the feedback scale sits. The naming engine watches
what the hero keeps doing. The feedback scale (the presence/warmth lean) is
one of the things the world reacts to, and it drives citizen warmth and the
morale temperature — but it is NOT the naming engine. Naming reads behavior
patterns directly.

THREE BEHAVIORAL BRANCHES, each with its own register of names:

1. SHOWED UP — engaged and completed. The hero who answers. Presence names:
   warm, earned, heroic-trending. ("Maple Street's Person.")

2. DIDN'T SHOW — never engaged; absent. The hero who isn't there. Absence
   names: the ghost register. ("The Invisible," "Nowhere to Be Seen.")

3. ABANDONED — engaged, then walked away. The hero who starts and leaves —
   the only branch where the citizen saw the hero's face before they turned
   around. Its own register, distinct from absence: ("All Talk," "The Tease,"
   "Almost.") Mechanically identical to ignoring (zero scale weight), but a
   different STORY — presence-then-absence, not absence — so a different
   name set.

WHY THREE BRANCHES, NOT ONE SCALE: A single cold-to-warm scale position cannot
encode the difference between ignoring and abandoning — both add zero weight,
yet they produce completely different names because the world experienced
different things. Reading behavior patterns directly captures this; reading a
scale position cannot. This also removes any "bad end" of the scale: absence
and abandonment names are not cold positions, they are observed patterns, the
same way "always rescues cats" would be a pattern.

CONSEQUENCE WITHOUT PUNISHMENT HOLDS: Every branch only ADDS a name. No branch
deducts, degrades, or reverses. "All Talk" surfacing does not erase "Maple
Street's Person" — the hero's history contains both, because the hero was
both, at different times. All names are permanent, available, and adoptable;
the player wears whichever reflection they choose. An absence- or
abandonment-name is a mirror of a real pattern, not a penalty — some players
will adopt "The Invisible" or "The Tease" on purpose.

WHY: The scale model defined a presence lean but could not explain how
absence and abandonment produce names, since both are mechanically zero on the
scale. Separating the NAMING ENGINE (reads behavior patterns) from the SCALE
(reads presence/warmth) resolves this: there are three nameable behaviors, each
its own branch, and the engine names the patterns that are actually there.

REPLACES: Supersedes the "names and unlocks STALL, never reverse" framing in
the zero-state entry. Corrected model: emergence does NOT stall during absence
— absence is itself a nameable pattern that feeds the DIDN'T-SHOW branch. Names
still never reverse. Consistent with the scale model, the zero-state entry's
reflect-never-escalate line, and the minor-objective outcome model (all 6/16).

STATUS: NOTED

DEFERRED (not designed here): how the three branches weight against each other,
how the engine handles a hero who is all three across a career (dominant
pattern vs. all patterns named), and the actual derivation of names — the
civic reward economy machine (HP-12). The branches EXIST; their engine stays
in the box.

---

DECISION LOG ENTRY

DECISION: HP and mentor challenges are independent parallel deepening
tracks. Resolves the Training Center / Hero Points contradiction.

The Training Center deepens hero powers through TWO independent, parallel
tracks:

1. HERO POINTS — the player-driven track. HP (earned from minor objectives,
   full carry) is spent on tiered hero-power upgrades in the Training Center.
   Player chooses when and which power, on their own schedule. No randomness.

2. MENTOR CHALLENGES — the world-driven track. The sponsor-challenge loop
   (prove a power → sponsor message → queued challenge → completion → deepening
   → cap → temporary boosts) deepens powers AND incentivizes experimentation
   with different powers, builds, and classes. The deepening and the nudge ARE
   the reward.

THE TRACKS ARE INDEPENDENT. They do not pay into each other. Mentor challenges
do NOT reward Hero Points — that is the one interaction that would muddy the
two faucets, and it is explicitly ruled out. Two doors to the same room: one
the player walks through on their own schedule (HP), one the world opens and
dares them through (challenges).

WHY: Canon Guard (City Layer pass) surfaced that the Hero Points entry
(May 8) locates HP spending on tiered Training Center upgrades, while City
Layer's deepening system is entirely sponsor-challenge-driven with no HP-spend
mechanic — leaving the HP sink homeless and the two May DRAFT entries
(Training Center Complete System, May 6; Hero Points, May 8) in tension. This
resolves it: the HP-spend entry is not a fossil to retire but the player-driven
half of a two-track system, with the challenge loop as the world-driven half.
Keeping the tracks independent (no cross-payment) preserves both as clean,
separate sinks and avoids designing the broader economy. City Layer requires
no change — it correctly treats HP as a run-layer output it does not own; the
Training Center houses both tracks.

REPLACES: Reconciles (does not retire) the Hero Points entry (May 8) and the
Training Center Complete System entry (May 6) — confirms HP-tiered-upgrades and
challenge-deepening coexist as parallel tracks rather than contradicting.

STATUS: NOTED

DEFERRED (not designed here — own session): the broader HP/deepening economy —
faucets and sinks beyond tiered upgrades; whether the class-mentor track
(class primaries) or companions involve HP; the post-unlock challenge-reward
structure (e.g., challenges shifting behavior once all primaries are unlocked).
This is HP-12 / a dedicated deepening-economy session. The two tracks EXIST and
are independent; their economy stays in the box.

---

DECISION LOG ENTRY

DECISION: Morale is a parallel city-state system, not part of the feedback
scale — and it produces no run-side mechanical effect. Resolves the
Cross-System Audit tensions between City_Layer and World_Feedback.

MORALE IS PARALLEL TO THE FEEDBACK SCALE. Morale and the feedback scale are
two different systems that both respond to player behavior. The feedback scale
is the narrative mirror (names, channel reactions, the world's read) — it
reflects, never rewards, never gates. Morale is a city-state system: a real,
earned output of Escort Defense missions (with a secondary trickle from minor
objectives), parallel to resources (Boss Fight) and intel (Horde Survival).
The feedback scale does NOT "drive the morale temperature." Any language
asserting that is in error.

MORALE HAS NO RUN-SIDE MECHANICAL EFFECT. The morale XP multiplier is removed.
Morale produces no mechanical reward in the run layer — there is no city→run
XP wire. Morale is mechanically real on the CITY side (it drives the city's
warmth, atmosphere, how lived-in the streets read) and inert on the RUN side.
This keeps the feedback layer's non-negotiable intact (the world's narrative
response never produces a mechanical reward) by ensuring morale, a separate
system, also produces no run reward.

MORALE DOES NOT GATE NAMING. Name emergence reads behavior patterns (the
three-branch naming engine, NOTED 6/16), not morale state. Any language tying
citizen name emergence to morale level ("high morale surfaces names, low
morale doesn't") is superseded and removed.

NO PENALTY: Consistent with consequence without punishment — low morale is
never a deduction or a stingier city; removing the multiplier removes the
question entirely, since morale now produces no run reward to withhold.

WHY: Cross-System Audit found four tensions (City_Layer / World_Feedback) all
rooted in one unanswered question: is morale part of the feedback scale or a
parallel system? Locked Run Design already answers it — morale is the named
city output of Escort Defense, parallel to resources and intel — so morale is
parallel by locked canon, and World_Feedback's "scale drives morale" framing
was the error. Removing the run XP multiplier resolves the §9 conflict at the
source rather than guarding it with a rule. City_Layer's omission of a city→run
XP wire was correct; World_Feedback §5 was the error.

REPLACES: Supersedes the morale XP multiplier (Morale — XP Multiplier and
City-Wide Scope, May 8) and any feedback-scale-drives-morale or
morale-gates-naming language in World_Feedback. Consistent with locked Run
Design (Escort Defense → morale), locked Guiding Principles, the hidden-scale
model, and the three-branch naming engine.

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Stage progression runs on three parallel mission "XP bars" that
together unlock the stage boss. (Refinement of the locked stage-progression
model — NOTED for integration; not yet folded into City_Layer.)

The three main mission types each fill a parallel stage-progression bar:
- RESOURCE BOSS (Boss Fight) — fills the resource bar (the big bad guarding
  necessary city resources; "resource boss" delineates it from the stage
  boss).
- ESCORT DEFENSE — fills the morale bar.
- HORDE SURVIVAL — fills the intel bar.

Each bar requires the same or a similar amount of completion to fill. As the
bars fill, they unlock narrative, atmospheric, and aesthetic elements of the
city along the way. When all three bars are full, the stage boss unlocks.
Defeating the stage boss advances the city to the next stage.

This refines, and is consistent with, locked Run Design: Run Design already
states all three mission types are structurally necessary to progress and that
the area/stage boss gates the next stage. This model specifies HOW the
non-intel mission types are necessary — each fills a required progression bar —
rather than replacing the boss gate. Resources remain Boss Fight's output;
nothing is dropped.

WHY: City_Layer §4 has specified stage progression only vaguely ("tied to
player progression and playtime," "overall run completion"). This names the
mechanism: three mission outputs as three progression bars, all required, boss
unlocks when all three are full. It makes the three mission types symmetric
(three tracks to one gate) and gives morale a clear, unique mechanical job (the
city's progression, not the player's) distinct from the narrative scale.

REPLACES: Refines (does not replace) the stage-progression language in
City_Layer §4 and the area/stage-boss gate in locked Run Design. Integration
target: City_Layer §4, with a deliberate Canon Guard pass against locked Run
Design.

STATUS: NOTED — captured this session; NOT yet integrated into City_Layer.
Integration (City_Layer §4 rewrite + Run Design consistency pass) is its own
beat next session.

---

DECISION LOG ENTRY

DECISION: World_Feedback is LOCKED.

World_Feedback moves from DRAFT to /locked/World_Feedback. It is now canonical
and constrains content below it.

What it locks: the feedback layer as a single hidden scale read through three
channel voices (Citizens, Superhero Community, Rex Flynn) that agree on the
event and disagree on its meaning; the scale reflects, never grades, gates, or
punishes — mirrors not gates applied to the narrative layer; name emergence as
a three-branch behavioral engine (showed up / didn't show / abandoned), read
from behavior, not from the scale or from morale; absence is voiced by the
channels, never penalized; morale is a parallel city-state system with no
run-side mechanical effect (no XP multiplier); Rex Flynn character
specification; minor objectives as world signal.

WHY: The document was reconciled against locked Run Design, Guiding Principles,
and the minor-objectives pillar, and rewritten to carry the June 16 feedback
work (the scale model, the zero-state/absence-is-voiced model, the three-branch
naming engine, the morale-is-parallel resolution). Canon Guard PASS. Cross-
System Auditor CLEAN with City_Layer (two prior MINOR tensions resolved: the §4
morale-state naming fossil struck; the morale-bar-vs-temperature disambiguation
deferred to the three-bar integration beat, as it concerns a NOTED entry not
present in either locked document).

REPLACES: Supersedes the World_Feedback DRAFT. DRAFT retired.

STATUS: LOCKED — June 16, 2026

---

DECISION LOG ENTRY

DECISION: City_Layer is LOCKED.

City_Layer moves from DRAFT to /locked/City_Layer. It is now canonical and
constrains content below it.

What it locks: mirrors not gates scoped to the post-tutorial city (the tutorial
arc gates by run type as onboarding only); tutorial arc buildings; four city
stages; the Training Center complete system with two independent parallel
deepening tracks (Hero Points tiered upgrades and mentor challenges, no
cross-payment); the Hero's Lair; the restoration model; city-wide morale as a
parallel city-state system with no run-side mechanical effect; and the
run-to-city flow with completion tiers and stacking mission outputs.

WHY: The document was reconciled against locked Run Design (completion tiers /
stacked outputs added; mission outputs confirmed), Guiding Principles (the
universal "no exceptions" mirrors-not-gates claim scoped to the post-tutorial
city, resolving the Canon Guard CONFLICT), and minor objectives (city-wide
morale, the HP two-track deepening model). Canon Guard PASS. Cross-System
Auditor CLEAN with World_Feedback.

REPLACES: Supersedes the City_Layer DRAFT. DRAFT retired.

STATUS: LOCKED — June 16, 2026

---

DECISION LOG ENTRY

DECISION: Migrate the build bridge to first-party tooling — Unreal Engine 5.8
plus Epic's official Claude Code plugin (unreal-engine-skills-for-claude-code)
driving Unreal's built-in MCP server. BlueprintEngine 2.0.0 and UE 5.7.4 are
retired.

DATE: July 22, 2026

WHY: Tool reliability is treated as foundational infrastructure, not an
optimization. The prior bridge was a paid third-party plugin requiring manual
recompilation against each engine version, and was drifting out of support as
UE 5.8 became the terminal 5.x release. First-party tooling on both ends removes
the recompile dependency permanently and is structurally more token-efficient:
the Epic plugin exposes meta-tools with on-demand toolset discovery rather than
a full tool catalog at session start, keeping the prompt cache warm.

Rejected alternative: continue on BlueprintEngine and migrate later. Rejected
because build targets accumulate against the current bridge, making migration
more expensive the longer it is deferred.

Noted at the time as not decisive: an unknown share of observed Claude Code
failures were attributable to novel-authoring fragility rather than the bridge,
and migration would not resolve those.

OUTCOME — VERIFIED SAME DAY: Migration completed and proven. Read-only bridge
test returned a full actor inventory in under 20 seconds with zero dialogs. The
approval-modal wedge that repeatedly froze the game thread under BlueprintEngine
did not occur once on the first-party stack. Two build targets completed
successfully through the new bridge, including one that self-caught a
render-blocking defect. The migration landed.

REPLACES: Supersedes the standing "stay on 5.7.4, defer the upgrade" position.
Amends CLAUDE.md §2.

STATUS: LOCKED


DECISION LOG ENTRY

DECISION: The run camera is PERSPECTIVE projection, not orthographic. The term
"isometric" in Run_Design §3 is to be read as descriptive of the camera's fixed
offset angle, not as a specification of orthographic projection. "Hades
distance" is the controlling reference.

DATE: July 22, 2026

WHY: Run_Design §3 as locked June 12, 2026 contained an internal contradiction:
"isometric" conventionally implies orthographic projection, while the Hades
reference is a perspective camera at a fixed offset. The two terms specify
opposite things, and a build target was correctly blocked on the ambiguity.

Perspective is selected on tone grounds. The locked tone constraint is
comic-book kinetic — Spider-Man, not Batman. Orthographic reads tactical,
gridded, and flat; it suits a game about reading a board. Perspective reads
kinetic and cinematic, preserves depth and dramatic framing, and supports the
"you are always power" posture of Unleash. Orthographic was rejected as fighting
the tone brief in every frame.

Remaining camera values — pitch, yaw offset, arm length, FOV, yaw authority —
are explicitly NOT locked by this entry. They are feel values and cannot be
judged in a document. They will be set by play-tuning against a provisional rig
and locked afterward from observed values.

REPLACES: Amends Run_Design §3, resolving the isometric/Hades ambiguity. Does
not otherwise alter the locked camera model.

STATUS: LOCKED


DECISION LOG ENTRY

DECISION: The run camera's initial framing values are locked as a starting
baseline: pitch -65, yaw offset 0, spring arm length 800, FOV 75. Perspective
projection per the prior entry this date.

DATE: July 22, 2026

WHY: Run_Design §3 locked the camera as an isometric offset at Hades distance
but specified no numeric values, which blocked a build target. These values were
established by play-tuning against a live rig in the editor rather than chosen
in the abstract, on the principle that framing is a feel judgment and cannot be
evaluated in a document.

Tuning path: began at the engine Top Down template defaults (pitch -90, arm
1500, FOV 90). Pitch -90 was rejected as straight-down top-down, definitionally
not the isometric offset canon describes. Arm length 1500 was rejected as tuned
for straight-down coverage and rendering figures too small at an angle. FOV 90
was rejected as a first-person-width value that shrinks subjects at frame
center. The final values were confirmed against the criterion that matters for
the encounter model: both the player and a stationary encounter node are legible
simultaneously, with enough forward view to see a node before reaching it.

These are a starting baseline, not a final answer. They are expected to move
once real combat, real level geometry, and class-specific traversal exist. This
entry establishes that the camera is now specified enough to build against —
not that it is finished.

REPLACES: Fills the numeric gap in Run_Design §3. Supersedes the provisional
Top Down template values.

STATUS: LOCKED
