# 🕺 Pool Party Dance-Off

A fun, single-file **mobile HTML rhythm game** inspired by a guy in an open pink
shirt going *off* at a Las Vegas pool party. Tap the falling beats in time and
he busts a new dance move on every hit — keep the combo alive and don't let the
🔥 **HYPE** meter run dry!

▶️ **Play:** https://talarari.github.io/tecktonik/

## How to play

- **Tap** a lane when its beat reaches the glowing hit line.
- **PERFECT** timing scores more and pumps the HYPE.
- Chain hits to grow your **combo** (and your score multiplier).
- If the **HYPE meter** empties, the beat drops out — game over.
- Desktop testing: keys `A` `S` `K` `L` (or arrow keys) map to the 4 lanes.

## Features

- 📱 Built for portrait mobile, touch-first, scales to any screen.
- 🎵 All music & SFX synthesized live with the Web Audio API (no asset files).
- 🎨 Everything drawn on `<canvas>` — palm trees, cabanas, a dancing crowd, and
  our hero in his pink shirt and shades.
- 🔥 Combo multipliers, HYPE meter, confetti when you're on fire, and a saved
  best score.
- 🗂️ Zero dependencies — a single `index.html`.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

> Tip: add `#auto` to the URL for an autoplay/demo mode.

## Deployment

Pushes to `main` are deployed to GitHub Pages automatically via
[`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).
