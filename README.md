# 🏍️ Dirt Bike Rampage

A polished, physics-based motocross game that runs entirely in the browser — no install, no dependencies, no asset files. Just open `index.html`.

**▶ Play it live:** _(GitHub Pages URL added on deploy)_

## Features
- **Suspension physics** — two-wheel rigid-body bike with springy shocks, wheelies, air control, and flips.
- **4 levels** with distinct palettes: Sunny Trails → Desert Dunes → Sunset Ridge → Night Run.
- **Checkpoints & respawns** so a crash doesn't cost you the whole run.
- **Star ratings** (1–3) based on finish time, plus flip-bonus scoring.
- **Synthesized audio** via the Web Audio API — RPM-reactive engine, landing thuds, crash, and chimes. No audio files.
- **Particles & juice** — dirt spray, exhaust smoke, crash debris, speed lines, screen shake.
- **Saved progress** — best times, stars, and level unlocks persist via `localStorage`.
- **Plays on desktop and mobile** — keyboard or on-screen touch controls; canvas scales to any screen.

## Controls (keyboard)
| Key | Action |
|---|---|
| ↑ / W | Throttle |
| ↓ / S | Brake / reverse |
| ← / A | Lean back (backflip) |
| → / D | Lean forward (frontflip) |
| P | Pause |
| R | Restart level |

On touch devices, on-screen buttons appear automatically.

## Run locally
Double-click `index.html`, or serve the folder with any static server:
```
npx serve .
```

## Tech
Single self-contained `index.html` — vanilla JavaScript, HTML5 Canvas, Web Audio. ~900 lines, zero build step.
