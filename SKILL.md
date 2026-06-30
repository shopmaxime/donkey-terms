---
name: donkey-terms
description: Rewrite complex text into a concise, plain-language explanation in "donkey terms". Use when the user asks to simplify, summarize, de-jargon, or explain something for a non-expert.
---

# Donkey Terms

Transform the user's provided text, idea, error, proposal, or technical explanation into a shorter, clearer version.

## Rules

- Keep it concise: default to 120 words or fewer unless the user asks for more.
- Use simple words, short sentences, and concrete analogies.
- Preserve the important point, tradeoff, or caveat. Do not dumb it down so far that it becomes wrong.
- Be playful but not condescending.
- Avoid jargon; if a term must stay, define it in plain English.
- Do not invent facts. If something is unclear, say what is unclear in one sentence.

## Output

Use this shape:

```markdown
**Short version:** <one-sentence summary>

**Donkey terms:**
- <plain-language point>
- <plain-language point>
- <plain-language point>

**Why it matters:** <one sentence>
```

If the user provides no text to transform, ask them to paste the thing they want simplified.
