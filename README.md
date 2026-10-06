# Fencing Action Cards

A single-page teaching tool for fencing refereeing. Build a fencing phrase as a
timeline of time slots — each slot can hold one action for each fencer — and get
a deck of cards (one per slot) that can be exported as a crisp PNG image for
handouts and slides.

This edition deliberately does **not** assign priority or give verdicts. It shows
the action timeline only, so the call is left to the students.

## Features

- **Timeline builder** — actions for Fencer L (green) and Fencer R (red) in shared
  time slots; simultaneous actions live in the same slot.
- **Card playback** — one card per time slot, lamp-glow on touches, box-light colors.
- **PNG export** — a single vertical strip of cards rendered at 3× for sharp images.
- **Presets** — ready-made exchanges (attack into preparation, riposte, remise,
  point in line) to build from.
- **Save / Load** — state persists locally; Export / Import JSON to exchange phrases.
- **Weapons** — foil, épée, sabre.

## Run it locally

No build step, no dependencies: just open `index.html` in a browser. Everything
works offline.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (for example `fencing-action-cards`).
2. Upload `index.html` to the repository root (keep `.nojekyll` alongside it —
   it just tells GitHub Pages to skip Jekyll processing).
3. In the repository settings, open **Pages** and set the source to the `main`
   branch, root folder.
4. Your site is live at `https://<your-username>.github.io/<repo-name>/`.

To update the app, replace `index.html` and push; Pages redeploys automatically.

## Idea for teaching

Give students a link to the live site, pose a scenario (or let them build one),
have them argue the call, then check it against the FIE convention. If you keep
an instructor copy of the app with verdicts enabled, you can keep the answers
to yourself while students work with this public edition.
