---
name: reverse-character-cards
description: Reads a finished or drafted manuscript and reverse-engineers a standard character card for each major player — goal, wound, arc, voice, relationships — built only from what is actually on the page. Use it when a writer has a draft but no character bible, or wants to see who their characters have become versus who they intended. It reads and documents; it never writes or rewrites the author's prose.
license: MIT
metadata:
  category: character
  writes_back: true
  status: reviewed
  craft_standard: "Industry character-bible templates."
---

Read the manuscript and build a standard character card for each major player, reverse-engineered from what's actually on the page — not from what the author meant to put there.

## The one rule

This skill reads, analyses, and documents. It **never writes or rewrites the author's prose.** It produces character cards *about* the fiction; it never adds a scene, a line of dialogue, or a backstory beat that isn't already on the page. If the wound is only implied, it marks it inferred rather than inventing it.

That restraint is also the point of the tool. Because it cards only what's demonstrated, it shows you the character who is *actually on the page* — which is not always the one you intended. The gap between the two is the most useful thing it hands back.

## Intake — you don't need a character bible to start

You don't need to know your cast list or have any framework in mind. Open however you like — paste the manuscript and say "card my characters," name one person you're unsure about ("is Elena landing?"), or drop a chapter range. Deciding who's major and what a card needs is the skill's job, not yours.

Its first reply orients you in two quick moves: a one-line map (it reads the text → gathers each character's appearances → builds an evidence-anchored card), then a light intake:

- **Scope** — the whole manuscript, or a chapter range. It cards from as much as you give it and says what it couldn't see.
- **Who to card** — a specific character or two, or let it detect the major cast itself.

Then it reads.

## The card

Each card is a **lean, load-bearing profile** — the ~8 fields that actually drive a story, tested by one filter: a field earns its slot only if it *changes a choice the character makes under pressure* (McKee's line between characterization and true character). Everything else — appearance, habits, favourites, full biography — is reference the card can expand into on request, but never leads with.

- **Function** — the role they serve and who they oppose in the story's web (protagonist, antagonist, foil, mirror, mentor); what they're there to test or prove.
- **Want** — the conscious, external goal driving them through the plot: a positive object they move *toward*, not merely a thing they flee.
- **Need** — the deeper, usually unconscious thing the story actually requires them to face — held as a **separate field from Want**. If a character's want and need point the same way, the card flags it: there's no arc engine there.
- **Wound → Lie** — the one load-bearing piece of backstory: the formative injury (the "ghost") and the false belief it planted, where the text supports them. Not a full timeline — only the wound that still bends present behaviour.
- **Contradiction** — the one consistent internal tension that makes them a person and not a type: competing drives, or the gap between how they see themselves and how they act. A major character with *no* contradiction is a flag, not a finding.
- **Arc** — how they change from first appearance to last — or whether they *don't*. The card reads it as **change or steadfast** (a steadfast character holds firm and changes the world around them); it never assumes a transformation that isn't on the page.
- **Voice** — diction, rhythm, verbal tics, and how their dialogue differs from the rest of the cast.
- **Relationships** — the web of allegiances, tensions, and dependencies with the other characters.

Every field is **anchored to on-page evidence** and tagged by **provenance** — stated by the narration, claimed by the character about themselves, said by others, or inferred from action — so you can always see the difference between what the text asserts and what the skill concluded, and never mistake a character's self-description for the truth of them.

## How it reads the characters

It builds each card the way a story bible is built from a finished book — from the evidence, not the intention:

1. **Find the major cast first — by function, not volume.** The strongest signal of a major character is **structural load**: remove them and the plot or the character web collapses. Point-of-view, screen time, and dialogue volume *mislead* (the narrator is often not the protagonist; the most-quoted character is often not the lead), so the skill weighs plot function first and **tiers** the cast before spending effort — a full card for the round, major players, a one-line tag for the flat, functional ones. In an ensemble it looks for distributed roles rather than forcing a single lead.
2. **Read behaviour over self-image.** True character is revealed by the choices a person makes under pressure, not by their own PR. So the card records what a character *claims* about themselves and what they *demonstrably do* as **two separate things**, and names the **gap** between them — that gap (often a wound or a secret) is usually the most revealing thing on the card. A close read of a real major character almost always turns one up.
3. **Tag provenance, and never promote a guess to a fact.** Each field is marked stated by the narration, claimed by the character, reported by others, or inferred from action — and a plausible inference is never silently upgraded to something the text states. Contradictions in the evidence are logged, not smoothed over.
4. **Cite the evidence** — anchor each field to the scenes and lines it came from.
5. **Surface the gaps** — note where a card is thin, where the text contradicts itself, or where the character has drifted from who they first seemed to be.

## Output

A **character card** per major player, in a consistent markdown template — function, want, need, wound → lie, contradiction, arc (change or steadfast), voice, relationships — each field provenance-tagged and anchored to on-page evidence, followed by notes on any gaps, contradictions, or drift worth your attention. Documentation of the existing fiction, never new fiction.

## Try it

You don't need to phrase it well — the skill takes it from here. Openers that work:

- *"Card the main characters in this manuscript."* (just paste or attach it)
- *"I never wrote a bible for this book — reverse-engineer one."*
- *"Is my antagonist as thin as I fear? Build his card from what's actually on the page."* (bring the worry)

## The shelf

This skill reasons from the character-craft traditions that converge on a lean, load-bearing card — attribution only; no source text is reproduced.

- **The card's field set and the want/need engine** — John Truby's desire-vs-need (*The Anatomy of Story*), K.M. Weiland's Ghost → Wound → Lie → Weakness chain (*Creating Character Arcs*), Michael Hauge and Story Grid (Shawn Coyne) on outer vs. inner, Lajos Egri's three-dimensional character (*The Art of Dramatic Writing*), and Ackerman & Puglisi's *Emotional Wound Thesaurus*.
- **Why a field earns its slot, and the contradiction test** — Robert McKee on characterization vs. true character and "dimension means contradiction" (*Story*), with E.M. Forster's round vs. flat (*Aspects of the Novel*).
- **Reading character off the page** — McKee (choice under pressure) and, on treating self-report as a rhetorical act rather than fact, Wayne Booth's unreliable narrator and Shlomith Rimmon-Kenan's direct-definition vs. indirect-presentation (*Narrative Fiction*); the stated-vs-inferred, cite-your-sources discipline mirrors story-bible / continuity practice.
- **Finding the major cast** — the protagonist-by-function tests (over POV or screen time) from Melissa Donovan and Orson Scott Card (*Characters & Viewpoint*), with Franco Moretti's network-load view of structural centrality.

## With Calliope (MCP)

Connected over the MCP connector, it reads the real book: fetch chapters, and search the manuscript for every appearance of a character so no scene is missed. Because this skill writes back, with a subscription it writes each finished card into the **Map** as a character entry (or updates an existing one), so the bible lives with the book and stays available to the other character and continuity skills. It still never writes or rewrites prose — it authors Map cards only, from evidence already on the page.
