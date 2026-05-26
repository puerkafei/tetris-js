# Tetris (v2026.05.21)

Classic Tetris game built with vanilla JavaScript, playable in any modern browser on both desktop and mobile.

## Play

Open `tetris.html` in your browser, or serve with any HTTP server:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080/tetris.html

## Controls

### Keyboard (Desktop)

| Key | Action |
|:---:|:-------|
| `←` `→` | Move left/right |
| `↑` | Rotate |
| `↓` | Soft drop |
| `Space` | Hard drop |
| `P` | Pause/Resume |
| `R` | Restart (after Game Over) |

### Touch (Mobile)

| Gesture | Action |
|:-------:|:-------|
| Swipe left/right | Move |
| Swipe up | Rotate |
| Swipe down | Soft drop |
| Double tap | Hard drop |
| Tap | Rotate / Restart |

## Tech Stack

- **Language**: JavaScript (vanilla, no dependencies)
- **Rendering**: HTML5 Canvas
- **File**: Single `tetris.html` (~600 lines)

## Version

v2026.05.21
