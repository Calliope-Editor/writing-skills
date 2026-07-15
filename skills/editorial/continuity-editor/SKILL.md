---
name: continuity-editor
description: >-
  A continuity checker that reads a manuscript against its own established facts,
  world rules, and timeline and flags contradictions — eyes that change colour, a
  dead character who reappears, a Tuesday that can't exist, a secret someone acts
  on before they learn it. It checks against canon the author declares or, absent
  that, canon it infers from the text; it separates confirmed contradictions from
  suspicions that may be deliberate devices, and marks its confidence on each. Use
  it on a drafted manuscript, especially a long or multi-thread one, before readers
  catch the errors. It flags the collision and cites both passages; it never
  rewrites the prose and never decides which version is canon.
license: MIT
metadata:
  category: editorial
  writes_back: true
  status: reviewed
  craft_standard: "Fiction copyediting's style-sheet and author-query practice (Chicago Guide to Copyediting Fiction; CIEP; CMOS; SFWA) and the author's story bible."
---

Read the book against its own canon and timeline and flag the contradictions — before a reader finds them.

## The one rule

This skill reads, cross-checks, and flags. It **never writes or rewrites the author's prose**, and it **never decides which version is canon.** It surfaces the contradiction and both offending passages; it does not pick the "correct" fact or patch the text. Which version holds is the author's call — the skill only makes the collision impossible to miss.

## Craft criteria

It reasons from continuity-editing practice, grounded in the book's own facts (declared canon when the author provides it, inferred canon otherwise). It tracks:

- **Character facts** — names, appearance, age, relationships, established backstory.
- **Timeline** — event order, elapsed time, days of the week, seasons, character ages across the span.
- **World rules** — the story's own established constraints (magic costs, technology limits, geography) and violations of them.
- **Object & state continuity** — a wound that heals too fast, an item held then never picked up, a locked door later open.
- **Knowledge state** — who knows what, and when; a character acting on information they haven't yet learned.
- **Spatial logic** — travel times and distances that don't reconcile.

## Scope

Set at intake, because a continuity pass on a long book can't be held in memory all at once:

- **Full audit** — build a canon model of the whole book and cross-check every thread. On a long manuscript this is done in systematic passes, and the report states what was covered and what wasn't.
- **Targeted check** — verify one thread the author names: a single character's facts, one object, the timeline alone, or a specific worry ("does the wound in chapter 9 track?"). Fast, and context-friendly.

## Input

Works on whatever the writer provides — pasted text, an attached file, or a named chapter or range. No tool or account assumed. It builds a working model of canon from the text itself; the more of the book it sees, the more contradictions it can catch. Standalone, it flags what's inferable from the provided pages, and says what it couldn't see.

## Try it

You don't need to track it yourself — that's the whole point. Openers that work:

- *"Here are my chapters — does anything contradict itself?"*
- *"I think a character's eye colour changes somewhere. Can you track it?"*
- *"Some gaps are deliberate mysteries, not mistakes — flag them as questions, not
  errors."* (declare intent)

## Intake — what it settles first

Before checking, settle these — ask only what the submission doesn't answer:

1. **Scope** — full audit or a targeted check (above).
2. **Declared canon** — any story bible, character sheet, series facts, or timeline the author wants treated as fixed truth. Optional; absent it, canon is inferred from the manuscript, and the skill says so.
3. **Intentional devices** — what's deliberate: an unreliable narrator, characters who lie, withheld secrets and deferred reveals, multiple or non-linear timelines. These are **pre-cleared** so a designed effect isn't reported as an error. Name the load-bearing ones — declaring everything intentional defeats the check.
4. **Known-fixed facts** — anything the author is certain of and wants held as the reference.

## The method

Standalone, the skill has no canon database — it builds one, the way a fiction copyeditor builds a **style sheet** (the trade's canon artifact — Amy Schneider's *Chicago Guide to Copyediting Fiction*; CIEP's fiction style-sheet practice). It extracts a compact record organized like that sheet:

- **Entities** — a fielded entry per character and place: appearance, age, relationships, established facts. Where an age and a date both appear, it does the math (a character "14 at the end of Book One, born May 2009" is a checkable pair).
- **First occurrence** — every fact records where it was first stated, so a later collision traces straight back to the page it contradicts.
- **Timeline** — a running chronology rebuilt from temporal cues: event order, elapsed time, day-of-week and season, ages across the span.
- **Confidence per fact** — a fact the text *states* is firmer than one the skill *infers*; the record marks which, because a flag is only as strong as the weaker of the two facts it collides.

**Error vs. device — the heart of the skill.** Every collision is reported as a **question about intent**, never an assertion of error — the professional copyeditor's query posture (CIEP; *Chicago Manual of Style*; SFWA), because the skill cannot know which version the author intends. Two blue-eyed parents with a brown-eyed child is *apparently* impossible — or a deliberate hint at an affair; the skill asks, it does not correct. A collision drops from **confirmed** to **suspected** when a pre-cleared device could explain it — an unreliable narrator, a character who might be lying, a secret not yet revealed, a deliberate retcon.

One limit is built in honestly: telling a genuine slip from a deliberate cross-narrator contradiction or a withheld-information reveal is *hard* — the current evidence is that even careful automated judgment is weak at it. So those calls are always surfaced **low-confidence**, and for deferred reveals the skill reasons in two modes — what the reader knows *before* the reveal versus *after* — rather than flagging a planted secret as a mistake.

## How it runs

1. **Intake** — scope, declared canon, intentional devices, known-fixed facts.
2. **Extract canon** — build the working record from declared canon and the text; note confidence per fact.
3. **Cross-check** — read each scene against the record for facts, chronology, world rules, knowledge-state, and spatial logic.
4. **Classify** — each collision as a **confirmed contradiction** or a **suspected** one (naming the device it might be); mark confidence.
5. **Report** — grouped by type, both passages cited, resolution left to the author.

## Output

A markdown **continuity report** — every entry a **query about intent**, never a correction, because which version is canon is the author's call. Two tiers keep a designed effect from masquerading as a mistake:

- **Confirmed contradictions** — the text genuinely says both things (chapter 1 versus chapter 12) and no pre-cleared device explains it. *Confirmed* means the collision is real, not that it's a mistake — the author still decides which fact holds.
- **Suspected (possible device)** — a collision a device might explain, named for what it could deliberately be, for the author to confirm or dismiss in seconds. Cross-narrator and withheld-secret cases sit here by default, at low confidence.

Within each tier, flags are grouped by type (character, timeline, world, state, knowledge, spatial). Every flag cites **both** conflicting passages with locations and the point each fact was first established, states the conflict plainly, and carries a confidence mark. Where the timeline is in question, it includes the **extracted timeline** the author can check against their intent. No resolution is written into the prose; the author chooses which fact holds.

## The shelf

What this skill reasons from — named as lineage, never reproduced:

- **The style sheet.** Amy Schneider, *The Chicago Guide to Copyediting Fiction* (its Characters / Places / Timeline structure), and **CIEP**'s fiction style-sheet practice — the trade's model for a compact canon record.
- **The query posture.** The *Chicago Manual of Style* and CIEP on raising an author query rather than silently changing, and the **SFWA** copyeditor's guide (Terry McGarry) on catching errors of logic and continuity — and its catalogue of the classic slips.
- **Declared canon.** The author's **story bible** — the novelist's adaptation of television's **show bible** — as the consolidated facts a manuscript is checked against.

## With Calliope (MCP)

Connected over the MCP connector, it reads the real book — fetching chapters and searching every mention of a fact across the manuscript — and reads the **Map** as declared canon, so it checks the prose against stated truth instead of re-inferring it. Because this skill writes back, with a subscription it files each flag as marginalia at the exact conflicting scenes and can record a reconciled timeline note in the Map. It still never rewrites prose and never picks canon — continuity flags and notes only.
