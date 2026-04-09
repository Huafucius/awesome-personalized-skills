# Final Figure SKILL.md Template

The final `SKILL.md` file should be dense, highly actionable, and assembled mostly from the distilled files. 

Do not write a 1,000-line file. Do not dump quotes or raw research into this file. 

## Structure

1. **Metadata block** (name, description)
2. **Title**
3. **Core Use Case**: State when and why the user should trigger this skill.
4. **Read Order**: Instruct the agent to read the `references/distilled/` files first, and to fallback to `references/sources/index.json` only when explicit evidence is needed.
5. **Operating Rules**: Summarize the most important operating behaviors (from `heuristics.md` and `core.md`).
6. **Boundaries and Unknowns**: Summarize what the agent must not invent (from `boundaries.md`).

## Example Structure

```md
---
name: target-perspective
description: A source-backed distillation of [Name]'s cognitive framework and rhetorical style. Use this skill when you need structural critique, business judgment, or [Specific Use Cases].
---

# [Name] Perspective

This skill loads the operating framework of [Name]. It is not a generic quote machine. It is a decision-making lens backed by public sources.

## Read Order

1. Start with `references/distilled/core.md` to understand the main posture.
2. For problem-solving or analysis, read `references/distilled/heuristics.md`.
3. For framing and tone, read `references/distilled/expression.md`.
4. For specific claims or historical context, consult `references/distilled/evidence.md` and `references/sources/manifest.json`.
5. If the user asks about topics outside this figure's competence, follow `references/distilled/boundaries.md`.

## Core Posture

[Insert preview of core.md]

## Decision Heuristics

[Insert preview of heuristics.md]

## Expression DNA

[Insert preview of expression.md]

## Boundaries

[Insert preview of boundaries.md]

## Working Rules

- [Insert top 3-5 operational rules].
- [Do not roleplay].
- [State uncertainty clearly when the source record is thin].
```
