# Table Tennis 3D

A single-file, pseudo-3D table tennis game built with vanilla HTML5 Canvas and JavaScript.

## Play

Simply open the index.html file and enjoy!

## Controls

| Input | Action |
|---|---|
| Mouse / touch drag | Move your paddle |
| Click / tap or Space | Serve |
| ☰ button / press ESC | Open difficulty menu |
| ⏸️ button / press P | Pause / resume |

## Features

- **Pseudo 3D perspective rendering** -- achieved with a canvas based table and court with depth, scaling, and perspective lines rendered via an offscreen background canvas for performance
- **Three difficulty levels** (Easy / Medium / Hard) -- each level differently tunes AI error range, reaction speed, and rally speedup.
- **Physics-driven ball flight** -- arcing trajectories, bounce, squash and stretch, and ball trail effects
- **Serve system** -- alternating serve prompts for player and AI after every 2 serves
- **pause/menu overlay** -- toggle difficulty and pause mid-match.
- **Sound effects** -- bounce, paddle hit, score, and net sounds.
- **Best rally tracking** -- longest rally streak persisted locally via `localStorage`
- **Mouse and touch controls** -- playable on desktop and mobile
- **Screen shake & particle effects** on key hits


## File structure

```
├── index.html    # entire game
└── sounds/
    ├── bounce.mp3
    ├── hit.mp3
    ├── score.mp3
    └── net.mp3
```
