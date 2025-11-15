# Canvas

A minimal, high‑performance drawing app focused on simplicity. Full‑screen black canvas, compact toolbar, smooth pen strokes, eraser that removes entire strokes, undo, clear, screenshot.

## Features

- Pen with color and thickness controls
- Smooth strokes using cubic spline smoothing and width EMA
- Eraser removes whole strokes via hit‑testing
- Undo and clear
- Screenshot export (PNG)
- Mobile and desktop pointer support

## Quick Start

- Open `index.html` directly, or run a local server:
  - `python3 -m http.server 8000` and visit `http://localhost:8000/`

## Controls

- `✏ Pen` / `Eraser` toggle
- Color picker for pen color
- Thickness slider for pen width
- `Undo` to revert the last action
- `Clear` to remove all strokes
- `Screenshot` to download a PNG



## License

MIT License. See `LICENSE` for details.

## Project Structure

- `index.html` — application UI and logic
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow
- `README.md` — project overview
- `LICENSE` — license file
- `.gitignore` — common local artifacts excluded from VCS
