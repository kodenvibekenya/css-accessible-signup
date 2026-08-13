# CSS Project 4 — Accessible signup theme

Theme a complete form across light/dark preference, interaction states, narrow screens, and reduced motion.

Companion notes: [CSS notes](https://kodenvibe.tech/notes/css/).

## Start your own copy

On GitHub, select **Use this template** → **Create a new repository**, choose whether it will be public or private, then clone your new repository and edit that copy.

**Time-box:** 90 minutes<br>
**Prerequisite:** all four CSS lessons and CSS Projects 1–3<br>
**After-lesson milestone:** you can use purpose-named tokens and preserve form usability in every tested state.

## Start

Open `index.html` and edit only `styles.css`. The form is a local visual exercise; it does not send data to a service.

## Acceptance checklist

- [ ] Purpose-named custom properties control text, surfaces, borders, accent, focus, and spacing.
- [ ] The form is readable at 320px, 200% zoom, and with long label/error text.
- [ ] Inputs and the button inherit the page font and have comfortable touch size.
- [ ] Labels remain visible; help text and required information do not depend on placeholders.
- [ ] Hover, `:focus-visible`, invalid, and disabled styles remain distinguishable without color alone.
- [ ] Light and dark preference tokens maintain readable contrast.
- [ ] Optional movement is subtle and removed by `prefers-reduced-motion`.
- [ ] Keyboard focus is never clipped, hidden, or covered.
- [ ] There is no page-level horizontal scrolling at narrow widths.

## Finish

Test keyboard, touch emulation, invalid submission, light/dark preference, and reduced motion. Explain what each token means rather than what color it contains.
