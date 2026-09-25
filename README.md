# Full HTML Game Without Resources

A small browser-based first-person ASCII world rendered entirely in a single HTML file. The project is intentionally self-contained: no external art, audio, or asset files are required.

## What is this?

This game is a lightweight pseudo-3D exploration demo built with plain HTML, CSS, and JavaScript. It renders a stylized terrain scene with:

- first-person movement
- mouse-look camera controls
- dynamic lighting and sky changes
- rain toggle
- simple NPC-like creatures and props
- a castle structure and river terrain
- ASCII-style raycast rendering

## Features

- Fully self-contained in one file: `html`
- No dependencies or build step
- Works directly in a modern browser
- Keyboard and mouse controls
- Procedural terrain and environment generation
- Atmospheric visual effects such as rain, shadows, and water-like refraction

## Run it locally

1. Open the repository.
2. Open the `html` file in your browser.
3. Move with `W`, `A`, `S`, `D`.
4. Use the mouse or arrow keys to look around.
5. Press `R` to toggle rain and `T` to advance the time of day.

## Controls

- `W / A / S / D`: move
- Mouse or arrow keys: look around
- Click the canvas: lock pointer
- `R`: toggle rain
- `T`: advance time of day

## Project structure

- `html` — the complete game implementation (HTML, CSS, and JavaScript in one file)
- `README.md` — project information and usage notes

## Notes

This repository is intentionally minimal and demonstrates how to create a complete browser game using only native web technologies. It is a good example of a compact, dependency-free game project.

## License

This project does not currently include an explicit license file. If you plan to reuse or distribute it, add a license of your choice before publishing.
