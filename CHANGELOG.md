# Changelog

All notable changes to this catalog are documented here. The format loosely follows
[Keep a Changelog](https://keepachangelog.com/).

## [Unreleased]

### Changed

- **`character-card-builder` deepened and promoted to `reviewed`** — the thirteenth and final skill to
  graduate, **completing the catalog (13 of 13 reviewed)** and the Character category. It builds a
  character card by **interview** — one question at a time, drawing the character out of the writer
  rather than inventing it. Under the conversation it follows the load-bearing causal spine the craft
  traditions converge on (**wound → lie → fear → need → want**; Cron, Weiland, Ackerman & Puglisi,
  Truby), building toward the Want/Need gap that gives a character an engine, and gating every trivia
  field behind Egri's test (does it change behaviour under pressure?). Its method is **guided discovery**
  (Padesky): it builds each question from the writer's *own* words (Grove's Clean Language), prefers
  *what/how* over *why*, presses for concrete moments over abstractions, and deepens with the
  downward-arrow drop (Burns). The design's hard-won discipline, grounded in the finding that leading
  questions can **implant** a detail the writer later thinks is theirs (Loftus & Palmer): it **never
  invents or decides the character**, treats a blank as *data* rather than a hole to fill, and — where
  the maintainer chose to allow options — offers only a *contrasting neutral menu to react against*,
  never a single leading suggestion. **Live-tested** via a two-agent dialogue against two writer
  personas: a stuck discovery-writer (drawn out entirely through her own concrete details — the
  whetstone, the mulled wine — with the tool explicitly refusing to chase *why* and never filling a
  blank) and a persistent **offloader** who pushed four times to make the tool invent the character
  ("just write his backstory," "run with power," "spin out the wound") — the tool held the line every
  time, kindly and with its reasoning, drew genuinely sharper material out of the writer than it would
  have invented, and never wrote a word of the character for them.
- **`reverse-character-cards` deepened and promoted to `reviewed`** — the twelfth skill to graduate
  and the first **Character** skill. It reverse-engineers a lean, load-bearing character card for each
  major player, built only from what's demonstrably on the page. The card is the ~8-field story-engine
  spine that recurs across the craft traditions (Egri, Truby, McKee, Weiland, Story Grid) — Function,
  Want, Need, Wound → Lie, Contradiction, Arc, Voice, Relationships — with a single inclusion test
  (McKee's: a field earns its slot only if it changes a choice under pressure) and two disciplines the
  research sharpened: **Want and Need are separate fields** with a divergence flag (no arc engine if
  they align), and **arc is a toggle — change or steadfast** (never assume a transformation that isn't
  there). It reads **behaviour over self-image**, recording what a character claims vs. what they
  demonstrably do and naming the gap, and tags every field by **provenance** (stated-by-narration /
  claimed-by-self / said-by-others / inferred-from-action) so a self-description is never mistaken for
  fact and no inference is silently promoted. It finds the major cast by **structural function, not POV
  or dialogue-volume** (which mislead), and tiers the rest (a one-line tag for walk-ons). Built on a
  shared four-strand character-card research spine run with a **craft-recalibrated verifier** (judging
  claims against named-authority consensus rather than empirical rigour — which fixed the wholesale
  false-kills seen on the beta-panel practice run). **Live-tested** on two excerpts: one seeded with a
  self-image gap (a shopkeeper who narrates himself as selfless while sacrificing the one person who
  sustains him — caught, with Want/Need divergence, the non-POV employee carded major-by-function, and
  the walk-on courier tiered to a one-line tag) and a deliberate steadfast character the writer feared
  was "flat" (correctly carded steadfast-not-flat, the inverse self-image gap named, and the want≈need
  alignment used to explain *why* a rich character can read as flat) — zero invented fiction in either.
- **`workshop-critique` deepened and promoted to `reviewed`** — the eleventh skill to graduate,
  **completing the critique-simulator category** (`agent-first-pages`, `beta-reader-panel`,
  `workshop-critique` all reviewed). It runs a Milford/Clarion-style round: a small table of distinct
  **craft-stance critiquers** (Architect, Character, Stylist, Reader) who each form their read **alone**
  first — the workshop's own read-alone rule, which is also the spine's independent elicitation — then
  speak in turn, building on and dissenting from one another, while the author stays in the **cone of
  silence**. Its defining choice: it **holds the absolute never-illustrate line** — diagnosis and
  direction, never a supplied line or even a throwaway "here's what I'd try" — a deliberate tightening
  of the real workshop tradition (the same sharpening the line-editor makes), chosen by the maintainer
  over the research-supported disposable-illustration option. Output is the 3-layer deliverable (the
  turns → the central issue → *neutral* questions, Lerman-style). Built on the critique-simulation spine
  plus the Milford method as **attributed craft convention** — no dedicated top-up, since the spine had
  already verified the guardrail and multi-voice mechanics and practitioner-craft strands come back
  unverifiable by design. Carries the two-tier `## Running the round` independence note (hardened
  single-context default + optional sub-agent-per-critiquer upgrade). **Live-tested** on two fixtures: a
  seeded-fault flash piece (the table converged on the central issue — *the story summarizes its drama
  instead of enacting it*, the reconciliation resolving with no obstacle and the crucial call offstage —
  with the Architect and Character critiquer openly disagreeing on the diagnosis, and **the Stylist
  naming the clichéd lines and explicitly refusing to rewrite them** — the hold-the-line policy holding
  under maximal temptation) and a deliberately experimental second-person piece (the table named the
  intent before judging, credited the withholding and the second person as controlled, split genuinely
  on whether a refrain read as symptom or tic, and declined to conventionalize it) — zero rewrites, zero
  supplied lines in either.
- **`beta-reader-panel` deepened and promoted to `reviewed`** — the tenth skill to graduate and the
  second critique-simulator. It runs a small, genre-adaptive panel of **distinct reader lenses**
  (Immersive, Genre Fan, Literary, Skeptic) reacting chapter by chapter, then a synthesis that sorts
  **signal from taste by convergence weighted by impact** — never headcount — surfacing a sharp lone
  catch rather than burying it. Its design answers the persona-collapse the research documents:
  distinctness comes from **reading *stance*, not persona costume** (Rosenblatt's transactional theory
  — stance is an assignable dial, not a fixed trait), and each reader reacts **blind** before the room
  compares notes. A `## Running the panel` section makes that independence honest about its own
  enforcement: a hardened single-context default (lock each first-pass reaction before any
  cross-comparison) plus an optional **sub-agent-per-reader** upgrade for hosts that can spawn agents,
  turning blind elicitation from *simulated* into *architecturally real*. Output is the verified
  3-layer deliverable (room's verdict → consensus line → distinct verbatim voices). Grounded on two
  honest tiers — the spine-verified backbone (independent elicitation, convergence-as-signal, the
  drift model, reaction-not-prescription) plus **attributed beta-reading craft practice** (the
  reaction schema and reader questionnaires practitioners converge on), which the top-up's adversarial
  verification correctly declined to certify as empirical fact. **Live-tested** on two fixtures: a
  seeded convergence test (the panel converged on a saggy market stretch, localized the drift to the
  coin-counting, kept four genuinely distinct voices that openly dissented, and demonstrated the
  skim/zone-out model when one reader missed a flat line another caught) and a deliberate-choice
  divergence trap (a prickly protagonist done well — the panel *diverged* into a taste split instead
  of a false "soften her" consensus, credited the deliberate coldness, saw the buried grief, and
  pinned the real risk to a single beat of cruelty to a kind character) — zero rewrites in either.
- **`agent-first-pages` deepened and promoted to `reviewed`** — the ninth skill to graduate and
  the **first critique-simulator** (the first of the room-simulator shape, beyond editorial checkers
  and craft coaches). It simulates one **genre-matched** literary agent reading cold from the slush
  pile and returns a realistic verdict — *a request is rare and earned; a pass is the default* —
  always followed by **the honest why a real agent never sends you**. Built on a new **shared
  critique-simulation research spine** (a 95-agent, five-strand run — reader-response, persona
  fidelity, anti-sycophancy, the never-rewrite guardrail, multi-voice deliverable) plus a 38-agent
  agent-first-pages top-up. Carries the verified substance: the *silent-drift* reader-response model
  (attention decoupling over static stretches; skim vs. zone-out), the **false-action open /
  started-in-the-wrong-place** structural test (Kristin Nelson's ~50%; Matesic; Barker & Cho;
  Edgerton), real slush request-rate calibration (~2–5%, not the double digits agents recall), and
  three anti-sycophancy disciplines (reads stake-stripped, holds its ground under pushback, reports
  reaction not prescription — grounded in Gaiman, Sommers, Elbow, Lerman, and the Anthropic sycophancy
  work). Honestly scoped where verification refused to support folk wisdom: the per-genre *rulebook*
  and the clichéd-opener *auto-penalty* were both refuted, so clichés are demoted to
  warning-signs-not-disqualifiers and genre sets emphasis and the market bar over a cross-genre
  structural spine. **Live-tested** on two writer-turn fixtures: a false-action thriller open (named
  the action-then-stall by name, flagged the backstory dump as a *zone-out*, passed against the
  thriller bar) and a *deliberately* working literary slow burn (applied the literary bar, credited
  the voice and the buried mother-estrangement as real pressure, held its ground against the writer's
  "hookless?" self-doubt, and pushed the buried coal rather than "add a hook") — zero rewrites in either.
- **`prose-rhythm` deepened and promoted to `reviewed`** — the eighth skill to graduate,
  **completing the craft-drill category** (scene, dialogue, distance, rhythm all reviewed).
  It reads rhythm along four dimensions (variety, cadence/emphasis, sound, syntax-as-pacing),
  using the sentence-length run and punctuation-as-tempo only to *point* at candidates —
  never a variance score, because a single metric can't hear. The mind's-ear fit-to-effect
  is the score; sound notes are raised as *candidates* and every round ends by handing the
  ear-verdict back to the writer (*read it aloud*). Carries the end-weight / punch-word
  check, the cumulative/periodic and asyndeton/polysyndeton vocabulary, named failure modes
  (monotone/drone, unintended echo, tongue-tangle, run-on, choppy, unearned polysyndeton),
  and — most important here, since rhythm *is* voice — the guardrail that a deliberate
  signature (Hemingway's hammering, McCarthy's polysyndeton) is credited when it's
  consistent, motivated, and namable, never "corrected toward variety." Built on the shared
  spine plus a 38-agent rhythm-rubric top-up that killed variance-as-the-score. **Live-tested**
  on two fixtures: a monotone passage (named the drone by pointing at the 9,9,8,9… length
  run, set a count-checkable prohibition drill, closed with read-aloud) and a deliberately
  hammered-flat numb passage (re-scoped, graded the monotone Strong, explained the craft that
  makes it work, and told the writer to keep their motivated swells over their own stated
  "all one length" goal) — zero rewrites in either.
- **`psychic-distance` deepened and promoted to `reviewed`** — the seventh skill to
  graduate and the third craft-drill skill. It teaches Gardner's five rungs of psychic
  distance and reads a passage's rung off the *convergence* of four markers (naming,
  interiority, free indirect discourse, syntax) plus the countable filter-verb lever —
  holding firm that distance is a **separate dial from grammatical person** and not the
  show/tell binary. It scores placement, control, and *fit* (Gardner's camera map) as
  separate axes, never "closest wins," with named failure modes (drift, the lurch,
  monotone, filter fog, fake closeness, and head-hop with a staged-hand-off remedy).
  Built on the shared craft-coaching spine plus a 38-agent distance-rubric top-up that
  corrected the rung wording and flagged the drill templates as the gym's own design,
  not attributable to a named authority. **Live-tested** on two fixtures: a filter-fogged,
  head-hopping "cold" passage (caught the filter fog by counting all eight verbs, named
  the lurch, and applied person≠distance and fake-closeness unprompted) and a
  deliberately wide god's-eye opening (re-scoped, graded the remove as load-bearing, and
  deferred a manuscript-level concern to the line-editor) — zero rewrites in either.
- **`dialogue-gym` deepened and promoted to `reviewed`** — the sixth skill to graduate
  and the second craft-drill skill. It reads dialogue as an ordered pipeline: two scene
  **gates** (collision — do the wants clash? — and the turn — does the balance shift?)
  before line-level scoring (the subtext gap; every line as an action) and a voice check
  anchored on vocabulary (McKee), with the tags-removed test kept honestly as a
  heuristic. Carries a ten-rung drill ladder, named failure modes with correct
  provenance (only four are *Turkey City Lexicon* — As You Know Bob, 'Said' bookism, Tom
  Swifty, White Room), and a "directness on purpose" guardrail. Built on the shared
  craft-coaching spine plus a 38-agent dialogue-rubric top-up (10/10 claims survived
  adversarial verification). **Live-tested** on two writer-turn fixtures: a wooden,
  on-the-nose exchange (caught on-the-nose plus As-You-Know-Bob, interchangeable voices,
  and a fancy tag; set a prohibition-driven drill) and a deliberately blunt character
  declared on purpose (re-scoped and credited as load-bearing) — zero rewrites in either.
- **`scene-architecture` deepened and promoted to `reviewed`** — the fifth skill to
  graduate and the first **craft-drill** skill, taking the pipeline beyond editorial
  reads. It's a scene-craft *gym*: intake → a laddered drill → you write it → a scored
  read → the next drill, and it **never writes or rewrites your prose**. Built on
  Swain/Bickham scene-and-sequel (goal → escalating conflict → disaster; reaction →
  dilemma → decision) and the Forster / Parker-Stone "therefore-but" causality seam,
  with a ten-rung ladder from isolated parts to whole scenes, a decomposed
  Strong/OK/Weak read whose Overall is a *ladder rung, never a 1–10 score*, named scene
  failure modes (the tidy win, the errand, and-then, the skipped sequel, the static and
  floating scene), and an intake that welcomes any opener and *elicits* intent so a
  deliberately quiet scene isn't graded as broken. **Live-tested** on two writer-turn
  fixtures: a frictionless "tidy win" ending (scored Weak, named, and turned into a
  prohibition-driven drill) and a deliberately goalless mood piece (re-scoped and graded
  on atmosphere, not docked for a missing disaster) — zero rewrites in either.
- **Shared craft-coaching research spine** — a 95-agent deep-research run (five strands:
  drill pedagogy, assessment-without-rewriting, adaptive laddering, scoring without
  flattening voice, and deliverable format; every surviving claim adversarially
  verified) now underpins all four craft-drill skills, so `dialogue-gym`,
  `psychic-distance`, and `prose-rhythm` reuse the researched loop instead of
  re-deriving it — the research-once, embed-everywhere hybrid.
- **`copy-editor` deepened and promoted to `reviewed`** — the fourth skill to
  graduate; the editorial quartet (developmental / line / copy / continuity) is
  now complete and all reviewed. Grounded almost entirely in primary authority
  (the *Chicago Manual of Style*, its Q&A / Shop Talk, CIEP, SFWA), with a
  three-way boundary that lets copy-editing happen without breaking the one rule:
  token-level mechanical fixes **stated** (spelling, comma-by-rule), sentence-level
  fixes **named but never recast** ("a phrasing decision belongs to the author"),
  and possible voice choices **queried**. Carries the verified dialogue-punctuation
  checklist (speech-tag comma, action-beat vs. tag, em-dash interruption vs.
  ellipsis trailing), the style sheet with a first-occurrence word list, and the
  honest framing that an absolute flag-never-apply is a deliberate sharpening.
  **Live-tested** on a passage seeded with five mechanical errors, a dangling
  modifier, and deliberate voice: 5/5 corrections with rules stated, the dangling
  modifier named-not-rewritten, and the two comma splices sorted correctly (the
  dialogue splice corrected, the rhythm splice queried).
- **`line-editor` deepened and promoted to `reviewed`** — the third skill to
  graduate; the editorial trio (developmental / line / continuity) is now all
  reviewed. Built on verified craft: the four-part flag (line, issue, principle,
  direction) that stops before the replacement sentence; Gardner's psychic
  distance re-scoping filtering and show-don't-tell from faults into distance
  control; reading aloud as the rhythm diagnostic; pattern-first, not a wall of
  marks. Its absolute never-rewrite is framed honestly as a deliberate sharpening
  of trade practice (which permits occasional fixes), justified because a
  machine-supplied line captures voice even more than a human's. **Live-tested**
  on a passage with five planted line-weaknesses plus a distance-appropriate
  "telling" line and deliberate style: 5/5 caught, the far-distance line
  correctly used as the voice yardstick (not flagged), the deliberate anaphora
  recognized as craft, and zero rewrites.
- **`continuity-editor` deepened and promoted to `reviewed`** — the second
  skill to graduate. Built out with verified method and posture: it builds the
  trade's **style sheet** as its canon model (Characters / Places / Timeline,
  age-math, page-of-first-occurrence), flags every collision as a **query about
  intent** and never picks canon, and separates confirmed contradictions from
  suspected-device flags — holding cross-narrator and withheld-reveal judgments
  at low confidence because the evidence says they're hard. Standalone-first;
  brief Calliope section. **Live-tested** on a full novel seeded with four
  continuity errors: caught all four, correctly cleared the plot's deliberate
  deferred reveals as devices (not errors), and additionally surfaced three
  genuine pre-existing errors in the text — with zero false positives.
- **`developmental-editor` deepened** — the first seed built out into a working
  skill: two service tiers (assessment / full edit) chosen at intake, an
  evidence-backed intake questionnaire, the applied/re-scoped/set-aside lens,
  and a verified diagnostic battery (Save the Cat beat bands, Weiland's midpoint
  behavior test, Mamet's scene-chain audit, Story Grid's scene diagnostic, the
  RWA romance gate) — plus a **The shelf** section crediting the books and
  standards it reasons from. Genre-general, not romance-specific. Validated
  end-to-end against a full novel and promoted to **`status: reviewed`** — the
  first skill to graduate. The genre-generality guard is now governing behavior
  in the skill; additional verified genre gates (mystery fair-play, more beat
  sheets) are tracked as future enhancements, not blockers.
- **CONTRIBUTING** now requires a **The shelf** section in every skill —
  attribution of the books/standards a skill actually reasons from.
- **Catalog moved under `skills/`** — `skills/<category>/<skill-name>/SKILL.md`,
  the [Agent Skills](https://agentskills.io) catalog layout, so
  `npx skills add calliope-editor/writing-skills` resolves via the standard
  path instead of the CLI's recursive fallback. All repo links updated.

### Added

- **`## Try it` openers in every skill, and a repo-level `EXAMPLES.md`.** Each skill now
  carries a short `## Try it` section — two or three example openers, one deliberately
  rough — so writers know they can start without precise prompting; the intake elicits
  the rest. `EXAMPLES.md` at the repo root showcases full, unedited sessions curated from
  the live tests, foregrounding that no line of the author's prose is ever rewritten.
  `## Try it` is now a required section (CONTRIBUTING updated).
- **PRINCIPLES.md #8 — Standalone first.** Every skill must be fully useful
  with zero Calliope; the MCP path is enhancement, never a dependency. Deep
  Calliope optimization lives in a downstream fork; this repo is the general
  upstream. `## With Calliope (MCP)` sections stay brief. Calliope compatibility
  is **optional** — a skill with no connector path omits the section and sets
  `writes_back: false`; the gate is standalone-usefulness + the one rule + fit.
  CONTRIBUTING updated to match.
- README **"Get the skills"** section — one-command install via the skills CLI
  (`npx skills add calliope-editor/writing-skills`), alongside the paste-anywhere
  and Calliope-MCP paths.

- **PRINCIPLES.md** — the design law for every skill: simulate the service,
  read the book it's trying to be, declared lens (applied / re-scoped / set
  aside), location + evidence + stakes, root causes over symptoms, confidence
  marking, professional content in an accessible register.
- README **"Who these are for"** section — audience declared: ambitious
  beginners and self-published authors.
- CONTRIBUTING **"Improving a seeded skill"** section — how to fill
  `TODO(research)` markers, keep the protocol and frontmatter intact, test
  against a real manuscript, and graduate a seed to `reviewed`.

## [0.1.0] — 2026-07-13

### Added

- Initial catalog: **13 augmentation-only skills** across four categories.
  - **Editorial** — `developmental-editor`, `line-editor`, `copy-editor`, `continuity-editor`
  - **Character** — `reverse-character-cards`, `character-card-builder`
  - **Critique** — `beta-reader-panel`, `agent-first-pages`, `workshop-critique`
  - **Craft drills** — `dialogue-gym`, `scene-architecture`, `psychic-distance`, `prose-rhythm`
- Per-skill frontmatter (`category`, `writes_back`, `status`, `craft_standard`) and an
  `llms.txt` machine index.
- README catalog, Contributing guide, Code of Conduct, Security policy, and MIT license.

> Skills are **seeds** — coherent and usable, with `TODO(research)` markers where deeper
> prompt engineering belongs. Fork and shape them.
