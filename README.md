# Gallery Wall Planner

A single-file, offline web tool for mocking up a framed gallery wall to scale.

**Live:** https://mccaffc.github.io/gallery-wall-planner/

Enter your wall dimensions, add artwork (or paste a whole spreadsheet of sizes),
set matte and frame widths, and get a to-scale layout plus the square footage the
arrangement needs. Drag pieces to arrange them by hand, or let it auto-pack into rows.

## Features

- **Wall + artwork dimensions** in inches or cm.
- **Matte & frame widths** — set defaults for everything, override per piece.
- **Paste from a spreadsheet** — `name, width, height [, matte, frame, qty]` per line; tabs or commas. Paste straight from Excel / Google Sheets.
- **Drag to arrange** — move any framed piece by hand; arrow keys nudge. *Auto-arrange* re-packs into tidy centered rows.
- **Live square-footage** — wall area, framed area, wall coverage %, and the overall arrangement size, with a warning when it doesn't fit.
- **57″ hang center-line** guide for installation.
- **Print / Save PDF** — a clean presentation view of just the drawing and stats.
- **Share link** — the entire layout is packed into the URL; copy it to send the exact plan to someone else.
- Everything is saved in the browser and works with no internet connection.

## How it's built

One self-contained `index.html` — no build step, no dependencies, no backend.
Open the file locally or host it anywhere static.

Designed with [Harmony](../harmony) (Workbench macrostructure, blueprint-calm theme).
