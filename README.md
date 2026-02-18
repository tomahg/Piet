# MasterPiets - Piet IDE

A standalone clone of the [MasterPiets Piet IDE](https://gabriellesc.github.io/piet/index.html) — a browser-based IDE for the esoteric programming language [Piet](http://www.dangermouse.net/esoteric/piet.html).

## Usage

Open `index.html` in any modern browser. No build step or server required.

## Features

- Grid editor with brush and bucket fill tools
- 20-colour Piet palette with command overlay
- Resize/clear grid
- PNG import and export (with configurable scale)
- Step-through debugger with run/pause/continue/stop
- Breakpoints
- Stack, pointer, and I/O visualization

## Changes from original

- **Fixed import/export** — replaced broken Jimp CDN dependency with native Canvas API
- **Single file** — everything in one `index.html`, no build tools needed
- **No site navigation** — standalone page, no external template dependencies
- **Iterative flood fills** — avoids stack overflow on large grids
