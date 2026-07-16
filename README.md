<p align="center">
  <img src="assets/logo.svg" alt="Writing Skills" width="440">
</p>

<p align="center">
  <strong>Augmentation-only <a href="https://www.anthropic.com/news/skills">Agent Skills</a> for fiction writers — an editor, a critique group, a character bible, and a craft coach that read your manuscript and never write a word of it.</strong>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-5E8480" alt="License: MIT"></a>
  <a href="#the-catalog"><img src="https://img.shields.io/badge/skills-13-5E8480" alt="Skills: 13"></a>
  <img src="https://img.shields.io/badge/works%20with-Claude%20%7C%20ChatGPT%20%7C%20Cursor-2B2722" alt="Works with Claude, ChatGPT, Cursor">
  <img src="https://img.shields.io/badge/augmentation-only-B7355E" alt="Augmentation only">
  <a href="https://github.com/calliope-editor/writing-skills/stargazers"><img src="https://img.shields.io/github/stars/calliope-editor/writing-skills?color=5E8480" alt="Stars"></a>
</p>

Every AI writing tool wants to draft for you. **These don't.** Each skill reads your book, critiques it, simulates a room it will face, or drills you on craft — and hands back diagnosis, reaction, and ranked feedback. Never prose. The words on the page stay yours; that refusal is the whole point.

Built as [Claude](https://claude.com) Agent Skills, usable in any Claude session, and made to connect to a real manuscript over the [Calliope](https://writecalliope.ink) MCP connector.

> ## 13 skills · 4 categories · 0 that write your prose
> Install one, point it at your manuscript, and get the read.

## Who these are for

**Ambitious beginners and self-published authors** — the writer with a draft and
no editor on retainer. Every skill gives the professional-grade read, never a
dumbed-down one; it explains craft terms at first use and assumes no MFA. Further
along than that? Each skill reads your context and drops the glossary. The design
law behind all of them is short and public: **[PRINCIPLES.md](PRINCIPLES.md)**.

## The catalog

*✅ marks a **reviewed** skill — deepened with researched craft rubrics and tested end-to-end against a real manuscript. The rest are usable and in active development toward that bar.*

### ✍️ Editorial — simulated editors, from the story read to the copy pass

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**developmental-editor**](skills/editorial/developmental-editor) ✅ | The big-picture read: structure, pacing, arc, stakes — an edit letter, before any line edits. | ✓ |
| [**line-editor**](skills/editorial/line-editor) ✅ | Sentence craft — rhythm, clarity, voice, overwriting. Shows the weak line and why; never rewrites it. | ✓ |
| [**copy-editor**](skills/editorial/copy-editor) ✅ | Grammar, punctuation, consistency, house style — each flagged with the governing rule, so you decide. | ✓ |
| [**continuity-editor**](skills/editorial/continuity-editor) ✅ | Reads the book against its own facts and timeline and flags the contradictions. Pairs with the Map. | ✓ |

### 🎭 Character — industry-standard cards

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**reverse-character-cards**](skills/character/reverse-character-cards) | Reverse-engineers a standard character card per major player, built only from what's on the page. | ✓ |
| [**character-card-builder**](skills/character/character-card-builder) | Builds a card from scratch, interview-style — one sharp question at a time. | ✓ |

### 🔍 Critique simulators — the rooms your book will face

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**beta-reader-panel**](skills/critique/beta-reader-panel) ✅ | A panel of distinct reader personas reacting chapter by chapter — confused, bored, delighted, lost. | ✓ |
| [**agent-first-pages**](skills/critique/agent-first-pages) ✅ | A literary agent's slush-pile read of your opening: request, or pass — and the honest why. | — |
| [**workshop-critique**](skills/critique/workshop-critique) ✅ | A Milford/Clarion-style critique round; the group speaks while you stay in the cone of silence. | — |

### 🏋️ Craft drills — get better on purpose

*Theory framed by your intent → a targeted drill → you write it → a ranked read of how you did → the next drill.*

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**dialogue-gym**](skills/craft/dialogue-gym) ✅ | Subtext, beats, and distinct voices — drilled and ranked. | — |
| [**scene-architecture**](skills/craft/scene-architecture) ✅ | Goal, conflict, disaster; scene and sequel — drilled and scored. | — |
| [**psychic-distance**](skills/craft/psychic-distance) ✅ | The five rungs of narrative distance, and controlling them on purpose. | — |
| [**prose-rhythm**](skills/craft/prose-rhythm) ✅ | Sentence variety, sound, and cadence — tuned and scored. | — |

\* **Tends canon** — connected to a Calliope book over MCP, these skills can write their findings back to your **Map** or **marginalia** (a character card, an edit letter, a continuity flag) — never your prose, and with a Calliope subscription. The rest return their output as text.

## Get the skills

**One command, 70+ agents.**
The catalog follows the [Agent Skills](https://agentskills.io) standard, so the [skills CLI](https://github.com/vercel-labs/skills) installs it into Claude Code, Cursor, Codex, Copilot, and friends — project-level by default, `--global` for everywhere:

```bash
npx skills add calliope-editor/writing-skills                      # the whole catalog
npx skills add calliope-editor/writing-skills --skill line-editor  # just one
```

**No installer — paste or attach, in any Claude session.**
Every skill is self-contained. Drop a skill's `SKILL.md` into any Agent-Skills-capable client, then paste your text, attach a manuscript file, or name a chapter range. No account, plugin, or subscription required. The skill works on exactly the text you hand it and returns its output as text or markdown.

**With Calliope — connect over MCP, work on your whole book.**
[Calliope](https://writecalliope.ink) is a manuscript-first writing app. Connect a skill to your Calliope book over the [MCP connector](https://writecalliope.ink/docs/mcp) and it reads the *real* manuscript — chapters in order, a search across the whole book, your **Map** (characters, arcs, timeline) and **marginalia** — instead of only the snippet you pasted. See how it fits together at **[writecalliope.ink/features/mcp](https://writecalliope.ink/features/mcp)**.

## The one rule

Everything here is **augmentation-only**. A skill may read, analyse, critique, teach, and — over MCP — tend your canon. **No skill may write or rewrite the author's prose.** A contribution that drafts, ghostwrites, or "rewrites in your voice" is out of scope by design. What you get back is diagnosis, reaction, and ranked feedback — the things a good editor, a good beta reader, and a good workshop give you — never a draft written for you.

## Contributing

Two ways in: **deepen a seeded skill** (fill its `TODO(research)` markers with researched substance) or **add a new one** that maps to a real service, room, or drill. Every contribution is measured against **[PRINCIPLES.md](PRINCIPLES.md)** and the one rule above. **[CONTRIBUTING.md](CONTRIBUTING.md)** has the skill format, how to approach an edit, and when a seed graduates to `reviewed`. Please also read the **[Code of Conduct](CODE_OF_CONDUCT.md)**.

## License

[MIT](LICENSE) — fork, adapt, and ship freely. Craft-method references (Gardner, Le Guin, Swain, Story Grid, the Chicago Manual of Style, and others) are named as methodology attribution only; no source text is reproduced.

## About

Maintained by the team behind [Calliope](https://writecalliope.ink) — the AI writing app that never writes your prose. If these skills are useful on their own, wonderful; if they make you want a manuscript-native home for them, that's where Calliope comes in.
