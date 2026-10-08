---
name: make-knowledge-cards
description: "Turn pasted articles or local Markdown and TXT files into concise, source-faithful knowledge cards. Use when the goal is to distill important concepts, not to browse the web, process PDFs, or create Anki decks."
---

# Make Knowledge Cards

Turn one supplied article into a small set of standalone knowledge cards that help a reader remember its most important ideas. Preserve the source's language unless the user requests another language.

## Accepted input

Use either text pasted by the user or a local `.md`, `.markdown`, or `.txt` file the user identifies. Read a local file before making cards. If the input is a URL, PDF, Anki deck, or request for a graphical interface, explain that it is outside this skill's scope and ask for pasted text or a supported local file instead.

## Select the knowledge

Read the whole source before drafting. Identify distinct ideas that are necessary to understand its main claim, method, mechanism, rule, or decision. Prefer ideas that have clear explanatory value over headings, transitions, rhetoric, and incidental detail.

- Merge statements that express the same idea, even when worded differently.
- Keep one concept per card. Split a compound point only when each part can stand on its own; otherwise keep the relationship together as one concept.
- Do not infer missing causes, definitions, qualifications, dates, evidence, or recommendations. Every assertion in a card must be supported by the source.
- Omit unsupported background knowledge, even if it would make the explanation more familiar or polished.

## Decide the count

Aim for 5–8 cards only when the source contains that many genuinely distinct, important concepts. If it contains fewer, return fewer cards and state briefly that the source did not support more distinct important points. If it contains more, select the 8 most central concepts and avoid overlapping coverage. Do not pad the result to meet a number.

## Card format

Give each card this exact, easy-to-scan structure:

```markdown
### 卡片 1｜[短标题]
**核心知识：** [one precise statement of the concept]
**简明解释：** [a plain-language paraphrase limited to information in the source]
**例子或自测：** [a source-provided example, or one answerable self-test question derived solely from the card]
```

Use a source example only when the source actually provides it. Otherwise write a self-test question that checks the card's core idea without introducing facts. Keep titles short and distinct. Do not add citations, source links, Anki syntax, graphics, or extra sections unless the user asks.

## Final quality check

Before responding, check that each card has one unique topic, that no two cards can be merged without losing an important distinction, and that every detail is traceable to the supplied text. Remove a card rather than guessing or repeating yourself.
