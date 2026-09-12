# Student Profile Builder

A small, static website that lets a student fill in a form about
themselves and instantly see a clean, printable one-page profile.

No frameworks, no backend, no build step, no network calls — just
`index.html`, `style.css`, and `script.js`. Open `index.html` in a
browser, and it works.

## Features

- **Live preview** — the profile updates as you type, no submit button
- **Evidence-only** — shows *only* what you entered; empty fields and
  sections are hidden; nothing is invented or auto-filled
- **Save / Load / Clear** — stores data in the browser via
  `localStorage` (stays on this device only)
- **Print / Save as PDF** — one click, fitted to a single A4 page
- **Accessible** — labelled inputs, keyboard-friendly, visible focus
  states, WCAG AA contrast

## Getting started

```bash
git clone https://github.com/<your-username>/student-profile-builder.git
cd student-profile-builder
open index.html   # or just double-click it
```

## Sections

About me · Subjects · Achievements · Activities & clubs · Skills ·
Interests · Goal

## Limitations

Data is stored per-browser only — no cloud sync, no accounts.

## License

MIT
