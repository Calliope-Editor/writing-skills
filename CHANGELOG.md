# Changelog

All notable changes to this catalog are documented here. The format loosely follows
[Keep a Changelog](https://keepachangelog.com/).

## [Unreleased]

### Changed

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
