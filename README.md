# 大嘴鸟历险记 — Pelican Rush

A 3D browser game built with Three.js. Control a pelican flying over the ocean — dive to catch fish, dodge rocks, boats and seagulls. No install, no build step: just open `index.html` or share the GitHub Pages URL.

## Play

**[Play Now](https://6kmfi6hp.github.io/pelican-rush/)**

## Controls

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move left/right | A / D or ← / → | Left joystick |
| Move up/down | W / S or ↑ / ↓ | Left joystick |
| Dive & catch fish | Space | Dive button (right) |

## Scoring

- Dive into the sea and catch a fish: **+10 pts**
- Combo catches multiply the bonus (+5 per extra catch)
- Survive: **+1 pt/sec**
- High score saved in localStorage

## Difficulty

Speed starts at 2× and increases by 0.5× every 30 seconds up to 10×.

## Tech

- Three.js r160 (CDN, no build step)
- Single `index.html`, zero dependencies
- All geometry procedurally generated (low-poly style)
- Works on desktop and mobile
