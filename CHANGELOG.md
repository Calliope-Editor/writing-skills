# Changelog

All notable changes to this catalog are documented here. The format loosely follows
[Keep a Changelog](https://keepachangelog.com/).

## [Unreleased]

### Changed

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
