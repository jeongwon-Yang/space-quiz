# Space Exploration Quiz — project rules

## What this is
A single-file quiz app: `index.html` contains all HTML, CSS and JavaScript. Open it directly via `file://`.

## Rules
1. **One file, no dependencies.** Keep everything in `index.html`. No frameworks, CDNs, build steps, web fonts or servers.
2. **Preserve both themes.** Use the CSS custom properties in `:root` and the `prefers-color-scheme: dark` override. Never hard-code a colour only for one theme.
3. **Respect motion preferences.** Every new animation must be disabled or toned down under `prefers-reduced-motion: reduce`.
4. **Keep it accessible.**
   - All interactions work by keyboard (Tab, ↑/↓, A–D / 1–4, Enter, Space).
   - Keep the visible `:focus-visible` ring; do not remove outlines.
   - Text contrast ≥ 4.5:1 in light and dark themes.
   - Decorative elements get `aria-hidden="true"`.
5. **Layout and type.** Narrow centred column (max ~440px), system sans-serif body at 14–16px; monospace only for the mission-control “telemetry” accents.
6. **Questions** live in the `QUESTIONS` array as `{ q, a: [4 options], c: correctIndex }`. Keep exactly 4 options per question and verify facts.
7. **Score logic.** One answer per question, score only increases on correct answers, and the celebration state appears only for scores ≥ 8.

## Before finishing a change
- Open `index.html` in a browser (light and dark), play a full round with the keyboard only, and check correct/incorrect feedback, score, progress bar and results screen.
- Confirm the browser console has no errors.
