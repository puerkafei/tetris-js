# Tetris (v2026.05.26)

Classic Tetris game built with vanilla JavaScript, playable in any modern browser on both desktop and mobile.

> **Created by:** OpenClaw + OpenCode (貂蝉) collaborative AI workflow.
> OpenClaw orchestrates the team; OpenCode (貂蝉) handles coding and debugging.

---

## Changelog

### v2026.05.26 (Current)

- Line clear animation — full rows flash before disappearing, just like the classic handheld Tetris
- Pause/Resume — on-screen button or press `P` on keyboard
- Double-tap hard drop on mobile (fixed: previously had no effect)
- Bug fix: multi-line clear no longer leaves ghost rows

[View on GitHub](https://github.com/puerkafei/tetris-js/releases/tag/v2026.05.26)

### v2026.05.21

- Initial release
- Keyboard and touch controls
- Bottom button panel for mobile

[View on GitHub](https://github.com/puerkafei/tetris-js/releases/tag/v2026.05.21)

---

## Play

[https://puerkafei.github.io/tetris-js/](https://puerkafei.github.io/tetris-js/)

## Controls

### Keyboard (Desktop)

| Key | Action |
|:---:|:-------|
| `←` `→` | Move left/right |
| `↑` | Rotate |
| `↓` | Soft drop |
| `Space` | Hard drop |
| `P` | Pause / Resume |
| `R` | Restart (after Game Over) |

### Touch (Mobile)

| Gesture | Action |
|:-------:|:-------|
| Swipe left/right | Move |
| Swipe up | Rotate |
| Swipe down | Soft drop |
| Double tap | Hard drop |
| Single tap | Rotate |

### Mobile Bottom Buttons

| Button | Action |
|:------:|:-------|
| ◀ ▶ | Move left / right |
| ↻ | Rotate |
| ▼ | Soft drop |
| ⏬ | Hard drop |
| ⏸ / ▶ | Pause / Resume |

## Tech Stack

- **Language**: JavaScript (vanilla, no dependencies)
- **Rendering**: HTML5 Canvas
- **File**: Single `index.html`

## Version History

| Version | Description |
|---------|-------------|
| [v2026.05.26](https://github.com/puerkafei/tetris-js/releases/tag/v2026.05.26) | Flash animation, pause, double-tap fix |
| [v2026.05.21](https://github.com/puerkafei/tetris-js/releases/tag/v2026.05.21) | Initial release |

Each release is downloadable as a source archive on the [Releases page](https://github.com/puerkafei/tetris-js/releases).
