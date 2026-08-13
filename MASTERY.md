# Mastery check — CSS Project 4 — Accessible signup theme

“Nailed it” is a three-gate decision. You must pass **all three** gates; a green automated run alone is not mastery.

## Gate 1 — Automated project checks

From the repository root, run:

```sh
node --test test/mastery.test.mjs
```

Every check must pass without skipping, deleting, or weakening a check.

- [ ] Purpose-named custom properties cover page, surface, text, border, accent, focus, and spacing roles.
- [ ] Controls inherit typography, retain usable minimum size, and define hover, focus-visible, invalid, and disabled states.
- [ ] Dark-preference tokens and a reduced-motion override are present alongside a flexible form width.

These checks cover selected functional and structural criteria. They do **not** claim to judge visual quality, usability, or accessibility conformance.

## Gate 2 — Applicable manual browser and accessibility checks

- [ ] Test keyboard focus and invalid submission in both light and dark preferences; every state remains distinguishable and readable.
- [ ] At 320 CSS pixels and 200% zoom with long labels, no focus ring or content is clipped and there is no page-level horizontal scrolling.
- [ ] Enable reduced motion and confirm optional movement is removed without hiding state changes.

Record the browser, viewport/zoom, input method, and any assistive technology used.

## Gate 3 — Explain back

Answer all three prompts in your own words. Each answer passes when it is accurate, points to concrete evidence in this project, and explains the reason or trade-off—not merely what a line says. A peer, mentor, or reviewer should ask one follow-up where an answer is unclear and record pass/revise for every prompt.

1. Choose three tokens and explain their semantic jobs rather than their current colors.
2. How does each interactive state communicate meaning in addition to color?
3. What changes under reduced-motion preference, and why does the interface remain understandable?

## Evidence record

Keep this short record in an issue, pull request, or learning log:

- Commit checked:
- Automated command, date/time, and result:
- Manual check environment and result for each item (or the documented not-applicable reason):
- Explain-back reviewer and pass/revise result for prompts 1–3:
- Help, tools, examples, or references used:
- Remaining limitation or next improvement:

## Honest boundary

This is formative practice, not a certification or proof of independent authorship. The repository owner can edit both code and visible checks, so CI records evidence about one revision rather than guaranteeing mastery. Manual observations and explain-back review remain necessary, and no single project demonstrates complete accessibility or professional readiness.
