# Immersive Human Cell — Three.js Demo

An interactive 3D tour through a stylised human cell, generated entirely in-code with [Three.js](https://threejs.org/). No external models or textures — every organelle is built from primitives and procedural geometry.

**[Live demo →](https://adrianhensler.github.io/three-js-cell-demo/)**

![Cell demo screenshot](https://raw.githubusercontent.com/adrianhensler/three-js-cell-demo/main/screenshot.png)

## Features

- Six interactive organelles with hover labels and click-to-document interactions
- Persistent selection highlight — click an organelle to pin it bright
- Semi-transparent cytoplasm so internal structures are always visible
- Per-organelle animations: nucleus breathing, mitochondria wobble, ER undulation, Golgi ripple, lysosome drift, centrosome microtubule pulsing
- Cytosol particle field (420 floating particles)
- WASD + Q/E movement, drag-to-orbit, scroll-to-zoom
- Organelle discovery log with completion banner
- ACESFilmic tonemapping + exponential fog for depth

## Organelles

| Structure | Highlight colour |
|---|---|
| Nucleus & Nucleolus | Violet |
| Mitochondria Cluster | Amber |
| Endoplasmic Reticulum | Cyan |
| Golgi Apparatus | Pink |
| Lysosome Network | Green |
| Centrosome | Ice blue |

## Controls

| Input | Action |
|---|---|
| Drag | Orbit camera |
| Scroll | Zoom |
| W / A / S / D | Drift forward / left / back / right |
| Q / E | Drift down / up |
| Shift | Move faster |
| Click organelle | Document & pin selection |
| Click again | Deselect |

## Stack

- [Three.js r128](https://threejs.org/) — rendering, geometry, materials
- `OrbitControls` — drag + zoom
- Pure vanilla JS/HTML, single file, no build step

## The prompt

> Recreate the cozy-room demo vibe, but for a human cell. Single-file Three.js, no assets. Include hover labels, click interactions, organelle status tracking, movement, and atmospheric lighting.

Generated and refined with [Claude Code](https://claude.ai/claude-code).
