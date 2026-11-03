# Clover — A Little Cow Farm

A peaceful isometric pixel-art cow farming game. No build step, server, API keys, or external assets are required.

## Features

- Feed, pet, milk, and rest cows; grow the herd. Cow stats, need icons, and care animations provide feedback.
- Plant clover, harvest it, sell it, or turn it into feed.
- Expand and design your farm: move, add, remove, paint ground, save, cancel, or reset.
- Four seasons and seven weather modes.
- Gradual day–night lighting, moving sun shadows, and illuminated barn windows and lanterns.
- Occasional jumping fish and safe cow wandering.
- Mouse-wheel zoom and drag-to-pan on empty ground.
- Right-side Herd, Farm shop, and User Guide drawers keep the farm visible. Browser-local saves support export/import.
- Season and weather selectors directly in the clock panel.
- Detailed outlined artwork rendered at 2100 × 1410, with crisp cow sprites.

## Run locally

Serve this directory with a static server: `python3 -m http.server 8000`, then open http://localhost:8000.

## GitHub Pages

In Settings → Pages, choose Deploy from a branch, select main and / (root), then save. The .nojekyll file keeps deployment buildless. Updates to main publish automatically after Pages is enabled.

GitHub Pages availability for private repositories depends on the account plan.

## Controls

- 1–6: Pet, Feed, Milk, Grow, Move, Sleep.
- Click a cow: Show stats and perform the selected care action.
- Milk: One click collects milk; a jug-filling animation shows progress.
- Pet: Raises affection and releases floating hearts.
- Move: Must be selected before dragging a cow.
- Mouse wheel / Z / X: Zoom.
- Drag empty ground: Pan.
- N: Switch day/night with a smooth transition.
- P: Pause ambient movement.
- Design farm: Enter Edit mode and click components directly.
- Escape: Clear selection or close a drawer.

The in-game User Guide includes detailed instructions, backup controls, and meadow notes.

## Source

- index.html: App structure and screen controls.
- style.css: Responsive layout and styling.
- game.js: Game logic, editor, procedural renderer, lighting, and ambient animation.

Original procedural artwork and game code created for Clover. Inspired by [Lakeside by nxtr1609](https://github.com/nxtr1609/lakeside). Lakeside source files and assets are not bundled.

Progress is stored per browser origin. To transfer a farm from another hosted copy, download its save from User Guide → Settings & backups, then load it on this copy.

