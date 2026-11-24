---
name: plain-writing
description: Plain, human writing style for any prose meant for people to read - docs, guides, READMEs, write-ups, explanations, messages, emails. Use when writing or revising such text, or when the user asks for writing that does not sound AI-generated, robotic, or full of filler.
---

# Plain writing

The goal is prose that reads like a careful human wrote it. That means none of the structural tics that signal automation: no em dashes, no scattered bold, no horizontal rules, no bullet lists where a sentence would do.

Cut anything the reader wouldn't miss. A section stays only if it answers a question someone will actually have. A reader should finish with a clear picture of the subject and where to find more, without wading through details they do not need.

No filler. Cut phrases like "saving time", "improving quality", "comprehensive solution", "seamlessly integrates". They say nothing. State facts.

Verify before writing. Check counts, file paths, and edge cases against the source. Do not approximate if the real value is findable, and do not invent details (options, values, advice) the source doesn't give.

## Patterns

- Open with the fact, not a framing sentence. "There are two ways..." not "This page describes two ways...". Never open with "This document covers..." or "This page explains...", because the reader already knows what they opened.
- Use connectives like "So" and "Here" when walking through a logical flow. They signal reasoning, not just sequencing.
- Example before rule: show the concrete case first, then the principle.
- Don't scaffold examples with "For example,". Just give the example.
- Avoid "The system..." as a subject. Name the actual component or action.

## AI tells

These mark text as generated. Rewrite the sentence rather than swapping in a synonym.

- "Not X, but Y" and "It's not X, it's Y". The negative half rebuts something nobody said. State Y directly.
- Groups of three by habit ("fast, reliable, and scalable") when there aren't three real things.
- Run-ups before the point: "Here's the thing", "Let's dive in", "It's worth noting that".
- Closing summaries: "In summary", "Overall", or a last paragraph that repeats what was said.
- Inflated words: pivotal, crucial, robust, seamless, powerful, game-changer, delve, leverage, utilize, showcase, foster, enhance.
- Tacked-on -ing clauses: "..., ensuring a smooth experience".
- "Serves as" or "functions as" where "is" works.
- Chatbot leftovers in text meant to stand alone: "I hope this helps", "Let me know if you have any questions".

## Rules

- Write in the language of the request. Keep another language only for quotes, legal references, and domain terms that need it.
- Present tense, active voice.
- Keep paragraphs short. Use bullets for separate items, options or steps, and full sentences for reasoning.
- Code, paths, and identifiers in backticks.
- No emojis.
- Bold only for genuine warnings that would be dangerous to miss on a skim. Bold everywhere means nothing stands out.
- No horizontal rules.
- No em dashes or en dashes, and no " - " or "--" standing in for one. They are a well-known giveaway. Use a period, comma, colon, or parentheses, or rewrite the sentence. Strip dashes from any text you are given before reusing it.
