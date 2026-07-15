# Contributing

Thanks for wanting to add to the catalog. New skills, and improvements to the
seeded ones, are both welcome — this file covers both paths. The design law every
contribution is measured against lives in **[PRINCIPLES.md](PRINCIPLES.md)**; read
it first, it's short.

## The one hard rule

**A skill may never write or rewrite the author's prose.** It may read, analyse, critique, teach, simulate a reader/editor/agent, and — over MCP — tend canon (Map, marginalia). It may *not* draft, ghostwrite, continue, or "rewrite in your voice." A PR that does is out of scope by design. Everything here is augmentation-only; that constraint is the point of the project.

## Improving a seeded skill

Most of the catalog is `status: seed` — coherent and usable, with the deep work
marked by `<!-- TODO(research): … -->`. Deepening a seed is the most valuable
contribution there is. How to approach it:

- **Fill TODOs with researched substance, not filler.** Each marker asks for
  something specific — rubrics, diagnostic questions, worked examples, drill
  ladders. Source them from real craft lineages and name the method or author
  (attribution only; never reproduce their text).
- **Keep the protocol intact.** Every skill establishes context before critique,
  declares its lens (applied / re-scoped / set aside), and obeys the output
  rules: location + evidence + stakes, root causes over symptom lists,
  confidence marked ([PRINCIPLES.md](PRINCIPLES.md) #2–#6). An edit that strips
  these regresses the skill, whatever else it adds.
- **Keep the frontmatter true.** `writes_back` is an integration signal for the
  Calliope app team — never flip it casually. `category` and `craft_standard`
  must keep matching the body.
- **Run it before you PR.** Point the skill at a real manuscript — public-domain
  novels are good subjects; *Pride and Prejudice* will happily absorb one more
  developmental edit — and say in the PR what you ran and how the output held
  up against the principles.

A seed graduates to `status: reviewed` when its TODOs are gone, the protocol is
embedded, it has been run end-to-end against at least one real manuscript, and a
maintainer has read what it produced.

## Adding a new skill

New skills are welcome when they map to something real: a service writers buy, a
room a manuscript faces, a drill a coach assigns — *simulate the service, not
the vibe*. Before adding one, check the idea isn't really a mode of an existing
skill; a deeper seed beats a wider catalog.

1. Pick the right category folder under `skills/`: `skills/editorial/`, `skills/character/`, `skills/critique/`, or `skills/craft/` (or propose a new one). The `skills/<category>/<name>/SKILL.md` shape is the [Agent Skills](https://agentskills.io) catalog layout — `npx skills add` depends on it.
2. Create `skills/<category>/<skill-name>/SKILL.md` where `<skill-name>` is kebab-case and matches the `name:` in the frontmatter.
3. Follow the frontmatter shape used across the repo:

   ```yaml
   ---
   name: your-skill-name
   description: >-
     Third person, one or two sentences: what it does and WHEN to use it
     (this is what triggers the skill). End with the refusal — it never writes
     or rewrites the author's prose.
   license: MIT
   metadata:
     category: editorial        # editorial | character | critique | craft
     writes_back: false         # true only if it tends canon over MCP; false also = no Calliope path
     status: seed               # seed | reviewed
     craft_standard: "The method / lineage it reasons from (attribution only)."
   ---
   ```

4. In the body, include: a one-line purpose; a `## The one rule` restating the refusal; `## Craft criteria` it reasons from; an `## Input` contract (pasted text / attached file / chapter range — no tool assumed); `## How it runs`; `## Output`; a `## Try it` section (two or three example openers, one deliberately rough — writers never need to prompt with precision); a `## The shelf` section naming the books, trade standards, and documents the skill actually reasons from (attribution only — and only what it truly draws on, nothing decorative); and — *if the skill has a Calliope enhancement path* — a **brief** `## With Calliope (MCP)` section describing the connected path (and, if `writes_back: true`, what it writes to the Map/marginalia — never prose).

**Standalone first ([PRINCIPLES.md](PRINCIPLES.md) #8).** The skill must be fully useful with no Calliope at all — paste text in, get the result. Keep the `## With Calliope (MCP)` section a short enhancement note, not a wiring diagram; deep tool-orchestration belongs in Calliope's downstream fork, not this general repo. A skill that can't function without the connector doesn't belong here. Calliope compatibility is **optional**: a skill with no meaningful connector path simply omits the `## With Calliope (MCP)` section and sets `writes_back: false`. The only hard requirement is that it works standalone, obeys the one rule, and fits the catalog.
5. Add a row for it to the catalog table in the [README](README.md).
6. Keep craft-method references as **attribution only** — name the method or author; never paste or reproduce their text.

## Seeds are fine

Skills here are seeds. It's OK to leave `<!-- TODO(research): … -->` markers where
deeper work belongs — a clear, honest seed is more useful than an over-claimed one.

## Pull requests

Open a PR with a short description of the skill and who it's for. Be kind and
constructive — see the [Code of Conduct](CODE_OF_CONDUCT.md).
