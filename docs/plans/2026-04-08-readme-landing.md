# README Landing Rewrite Plan

**Goal:** Rework the repository README into a stronger GitHub landing page while preserving the project's human-centered thesis and the two-category index model.
**Scope:** Update `README.md` copy and structure, add `.worktrees/` to `.gitignore`, and create the minimum docs files required by the workflow. Do not add fake repos, new categories, or self-owned skills sections.
**Architecture:** The README should behave like a landing page first and an index second. The opening must communicate identity, credibility, and action quickly; the full tables remain, but only after a tighter hero, selection logic, and clear navigation.
**Success criteria:** The README keeps only `Figures` and `Books` as index categories, strengthens the hero and GitHub formatting, explains why the repo matters, preserves only verified repositories, and adds clear contribution/roadmap cues without contradicting current project reality.

---

## Docs Impact

| File | Action | What changes |
|------|--------|-------------|
| `docs/README.md` | Create | Add the docs index required by the workflow |
| `docs/plans/2026-04-08-readme-landing.md` | Create | Record the plan and verification criteria for this README rewrite |
| `.gitignore` | Update | Ignore `.worktrees/` for future isolated task execution |
| `README.md` | Update | Reposition the repository homepage for stronger GitHub readability and promotion |

---

## Tasks

### Task 1: Establish workflow docs and repo hygiene

**Files:**
- Create: `docs/README.md`
- Create: `docs/plans/2026-04-08-readme-landing.md`
- Modify: `.gitignore`

**Steps:**
1. Write acceptance criteria in this plan
2. Verify `docs/README.md` is missing and `.gitignore` does not ignore `.worktrees/`
3. Add the minimum docs files and ignore rule
4. Re-check file presence and ignore rule
5. Commit: `docs: record README landing rewrite plan`

---

### Task 2: Rewrite README as a stronger landing page

**Files:**
- Modify: `README.md`

**Steps:**
1. Define acceptance criteria in this plan
2. Verify the current README lacks a stronger GitHub-style hero, featured section, and selection logic
3. Rewrite the README while keeping only `Figures` and `Books` as index sections
4. Review copy for natural, human-sounding Chinese-first bilingual tone
5. Update docs if needed
6. Commit: `docs: strengthen README landing page`

---

## Verification (Phase 5)

- [ ] `git diff --name-only` matches the planned file set
- [ ] `README.md` contains only `Figures` and `Books` as index sections
- [ ] `README.md` contains a stronger hero, featured entry point, selection criteria, roadmap, and contribution CTA
- [ ] `docs/README.md` exists and references this plan
- [ ] `.gitignore` includes `.worktrees/`
- [ ] `git status` is clean
