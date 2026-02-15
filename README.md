# Tug of War Arabic Spelling Game (React + Teacher Dashboard)

This app is a browser-based Arabic spelling tug-of-war game with a built-in teacher dashboard.

## Features
- Teacher dashboard to add/edit/remove rounds.
- Per-round setup includes:
  - target Arabic word,
  - prompt/description,
  - letter group constrained to 9–10 letters.
- Two-player tug-of-war gameplay with timer, score tracking, and round feedback.

## Tech stack
- React 18 (UMD via CDN)
- ReactDOM 18 (UMD via CDN)
- Babel Standalone (in-browser JSX transform)
- Tailwind CSS (CDN)

> Note: This version depends on CDN assets, so internet access is needed when loading the page.

## Run locally
```bash
python3 -m http.server 4173
```
Then open:
`http://localhost:4173`
