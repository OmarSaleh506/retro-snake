# retro-snake

A classic Snake game with a retro terminal aesthetic — CRT scanlines, phosphor glow, and all. Works on desktop and mobile. No dependencies, no build step.

**[Play online →](https://omarsaleh506.github.io/retro-snake/)**

## Play

Download or clone the repo, then open `index.html` in any modern browser. That's it.

```bash
git clone https://github.com/OmarSaleh506/retro-snake.git
cd retro-snake
open index.html   # macOS
# or just double-click index.html in your file manager
```

## Controls

| Input | Action |
|---|---|
| `↑` `↓` `←` `→` or `W` `A` `S` `D` | Move (desktop) |
| Swipe | Move (mobile) |
| D-pad buttons | Move (mobile) |
| Any key / Tap | Start / Restart |

## Features

- Retro terminal look — black background, phosphor green snake, monospace font
- CRT effects — scanlines, vignette, game-over screen flicker
- Snake grows as you eat, score tracked in the HUD
- High score persisted across sessions via `localStorage`
- Speed increases every 5 food eaten (150ms → 60ms min)
- Wall wrap-around — exit one side, enter the other
- Mobile support — responsive canvas, swipe controls, on-screen D-pad
- Single HTML file — no frameworks, no bundler, no install

## Screenshot

```
▓▓ SNAKE ▓▓

SCORE: 0080          HIGH: 0240
┌────────────────────┐
│  ░░░░░░░░░░░░░░░░  │  ← scanlines
│                    │
│    ████▓  ·        │  ← snake + food
│                    │
│                    │
└────────────────────┘

↑ ↓ ← →  OR  W A S D  TO MOVE
```

## Built with

Vanilla HTML · CSS · Canvas API — 365 lines, zero dependencies.
