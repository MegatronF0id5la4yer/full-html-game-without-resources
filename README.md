# Full HTML Game Without Resources

This repository contains a single-file browser game built with plain HTML, CSS, and JavaScript. The entire experience is contained in the `html` file, with no external images, audio files, or asset packs required.

## Overview

This project is a compact first-person survival-style prototype that renders a stylized ASCII world directly in the browser. It includes:

- WASD movement and mouse-look camera controls
- a procedural pseudo-3D terrain and environment
- dynamic lighting and sky variation
- collectible souls and batteries
- a hostile creature that patrols and chases the player
- a bell objective and safe campfire zones
- rain effects and a simple HUD

## Features

- Self-contained game logic in one file: `html`
- No build step or dependencies
- Runs in a modern browser without external resources
- Uses native canvas rendering and simple game systems
- Includes touch controls for mobile-style interaction
- Designed as a lightweight demo for HTML/CSS/JS game experiments

## Run it locally

1. Open the repository in your browser or serve it locally.
2. Open the `html` file directly in a browser or use a local static web server.
3. Start the game from the intro screen.
4. Use the keyboard or pointer controls to explore the area.

### Controls

- `W / A / S / D`: move
- Mouse: look around
- `Shift`: sprint
- `Ctrl` or `C`: crouch
- `Space`: jump
- `F`: toggle flashlight
- `E`: ring the bell
- `Q`: change render quality
- `R`: toggle rain

## Project structure

- `html` — the complete game implementation
- `README.md` — project overview and instructions

## Notes

This repository is intentionally minimal and demonstrates how to build a playable browser game using only native web technologies. It is a good example of a dependency-free, single-file game project.

## License

This project does not currently include a license file. If you plan to reuse or distribute it, add a license before publishing.
