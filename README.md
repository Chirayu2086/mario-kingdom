# 🍄 Mario Kingdom

A colorful, browser-based pixel platform adventure built with **vanilla HTML, CSS, and JavaScript**. No bundler, external libraries, or runtime dependencies.

## Play

Open **[index.html](./index.html)** in a modern browser, or run a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls

| Action | Keyboard | Touch |
|---|---|---|
| Move | A / D or ← / → | On-screen arrows |
| Jump | Space, W, or ↑ | Jump button |
| Pause / resume | P | Pause button |
| Toggle sound | M | Sound button |

## Features

- Side-scrolling platform game with parallax scenery, platforms, pipes, and a castle finish.
- Coins, score, lives, patrolling enemies, stomp interactions, and particle effects.
- Keyboard and mobile touch controls.
- Sound effects with a mute toggle, pause/resume, restart, and win/lose states.
- Responsive layout and reduced-motion-aware interface styling.

## Project structure

- `index.html` — complete game and interface.
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow.

## Deploy with GitHub Pages

1. Open **Settings → Pages** in the repository.
2. Set the build and deployment source to **GitHub Actions**.
3. Push to `main); the included workflow publishes the static site.

The game is an original fan-made platformer inspired by classic side-scrolling games. It is not affiliated with or endorsed by Nintendo. Names, characters, and trademarks belong to their respective owners.
