# Automated project grade — CSS Project 4 — Accessible signup theme

GitHub grades this project without waiting for a KODE Ń VIBE reviewer.

## The pass rule

- **PASS — Nailed it:** every required check passes in one run.
- **REVISE — Keep building:** one or more required checks fail.

There is no averaging and no partial-pass score. Do not delete, skip, rename, or weaken a check. Fix the project, push again, and GitHub replaces the result with a new grade for that commit.

## Automatic learner flow

1. On the KODE Ń VIBE starter, choose **Use this template** to create your own repository.
2. Create an attempt branch, for example `git switch -c attempt/my-project`. Keep the untouched starter on `main`.
3. Build the acceptance checklist, commit, and push the attempt branch. GitHub Actions starts the grade automatically; opening or updating a pull request to `main` is graded too.
4. Open **Actions → Automated project grade**. Read the failed check names and logs if the result says **REVISE**.
5. When the job summary says **PASS — NAILED IT**, save that run link as evidence.

Every repository's `main` branch is intentionally quiet, so unfinished starter code does not send false failure alerts. Grading starts automatically when you push an attempt branch or open a pull request to `main`.

## Run the same grade locally

From the repository root, run:

```sh
node --test test/mastery.test.mjs
```

Every check must pass without skipping, deleting, or weakening a check.

- [ ] Purpose-named custom properties cover page, surface, text, border, accent, focus, and spacing roles.
- [ ] Controls inherit typography, retain usable minimum size, and define hover, focus-visible, invalid, and disabled states.
- [ ] Dark-preference tokens and a reduced-motion override are present alongside a flexible form width.

These checks cover selected functional and structural criteria. The individual test names are the grading rubric; a failed name identifies what to revise.

## Optional confidence check — not graded

No reviewer is required for the automated pass. These quick checks are still worth doing because code tests cannot see every visual, usability, or accessibility problem:

- [ ] Test keyboard focus and invalid submission in both light and dark preferences; every state remains distinguishable and readable.
- [ ] At 320 CSS pixels and 200% zoom with long labels, no focus ring or content is clipped and there is no page-level horizontal scrolling.
- [ ] Enable reduced motion and confirm optional movement is removed without hiding state changes.

## Optional explain-back — not graded

Use these prompts to check your own understanding. They do not need a reviewer and they do not change the GitHub grade.

1. Choose three tokens and explain their semantic jobs rather than their current colors.
2. How does each interactive state communicate meaning in addition to color?
3. What changes under reduced-motion preference, and why does the interface remain understandable?

## Evidence to keep

GitHub keeps the commit, logs, and grade automatically. Save only:

- the commit SHA;
- the successful Actions run URL; and
- one sentence about what you would improve next.

## Honest boundary

**PASS means every published requirement checked by this project passed on one revision.** It is formative evidence, not a certificate or proof of independent authorship. A learner controls their copy and can edit visible tests or workflows, and automation cannot prove complete usability, accessibility, durable understanding, or professional readiness. Keep the supplied checks unchanged if you want the result to remain meaningful.
