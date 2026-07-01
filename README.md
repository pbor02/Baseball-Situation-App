# Situation Board

A single-file baseball coaching board for sketching defensive alignments and
game situations on a tablet or laptop. Built with inline SVG and vanilla
JavaScript — no build step, no dependencies.

## Features

- Drag the 9 defensive players anywhere on the field
- Tap a base to place or remove a runner
- Tap the grass to drop the ball at that spot
- Tap the OUTS indicator to cycle through 0 / 1 / 2 outs
- Draw-arrow mode for sketching plays, with a button to clear drawings
- Preset situations (runners on base + outs) via the dropdown
- Reset button restores the default alignment, situation, and drawings
- Touch handling tuned to avoid page scroll/zoom while dragging on tablets

## Run locally

Just open `index.html` in a browser — no server or install required:

```
open index.html
```

(or double-click the file / drag it into a browser tab)

## Deploy

Deployed to Vercel as a static site (no framework, `index.html` served at
the root). To redeploy after making an edit:

```
vercel --prod
```
