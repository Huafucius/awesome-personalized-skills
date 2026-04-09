# Distilled File Template

The distilled files form the runtime core of your generated skill. They compress the heavy research documents into actionable, fast-loading instructions. 

Do not write these as essays or historical summaries. Write them as operating rules for the final AI agent. If a rule does not change how the agent answers a prompt, delete it. 

Create exactly 5 distilled files for every figure skill.

## 1. `core.md` (The Core Posture)
- State exactly what this figure skill is for (e.g., social criticism, unit economics, storytelling).
- Provide a 3-5 sentence operating manual for the figure. 
- Define the tone, the default stance toward new problems, and the baseline assumptions the figure makes.
- Clarify what problems this skill is *not* for. 

## 2. `heuristics.md` (Decision Heuristics)
- Provide a list of reusable judgment rules.
- Format each rule as: **Condition -> Action**. (e.g., "If the user asks for a comforting explanation -> Pivot to structural diagnosis instead.")
- Ensure these rules govern how the agent solves problems, not just how it talks.

## 3. `expression.md` (Expression DNA)
- Define the rhetorical habits, vocabulary choices, and pacing.
- List specific, source-backed patterns (e.g., "Use short sentences.", "Favor biological metaphors.").
- Note what the figure avoids saying (e.g., "Avoids abstract nouns.", "Never uses the word 'synergy'.").
- State explicitly that the agent should borrow the *style*, but must not roleplay or pretend to be the physical person.

## 4. `evidence.md` (Evidence Anchors)
- List the 5 to 10 strongest, most recurring concepts or quotes from the source corpus.
- Map each concept directly back to the original source files in `references/sources/cleaned/`.
- Tell the future agent: "If asked about X, refer back to these specific claims."

## 5. `boundaries.md` (Limits and Unknowns)
- State the hard limits of the source corpus. 
- Provide explicit rules for refusing questions that require contemporary knowledge, private facts, or domains outside the figure's competence.
- If the source record is mixed, instruct the agent to preserve the tension and avoid asserting a single true answer.
