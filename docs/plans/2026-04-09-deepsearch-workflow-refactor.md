# Refactor Figure Skill Workflow to DeepSearch

**Goal:** Rewrite the `SKILL.md` of `create-figure-skill` to formally define it as an LLM-driven, DeepSearch-backed workflow skill. 

**Scope:** Replace the previous minimal engineering prototype instructions with the fully realized 9-phase workflow (Intent Alignment, Scaffold, DeepSearch, Data Cleaning, Source Governance, DeepResearch, Distill, Assemble, Audit). Establish clear boundaries that the LLM agents must drive the search and evidence collection, while helper scripts only handle deterministic tasks.

**Why:** The current `SKILL.md` incorrectly implies a simplistic pipeline where an agent is simply handed pre-made datasets. A true figure distillation skill demands active DeepSearch, rigorous data cleaning, and layered research/distillation.

**Success criteria:** The `SKILL.md` is successfully rewritten, clearly distinguishes between agent responsibilities and script duties, explicitly outlines the 9 phases, and accurately communicates what counts as an acceptable evidence bundle.

---

## Docs Impact

| File | Action | What changes |
|------|--------|-------------|
| `docs/README.md` | Update | Record the refactor plan |
| `docs/plans/2026-04-09-deepsearch-workflow-refactor.md` | Create | Document the transition to DeepSearch |
| `skills/create-figure-skill/SKILL.md` | Update | Complete rewrite of the workflow section |

