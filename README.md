# Neil's Land — A Vision for 10 Acres

A small static website presenting a 10-acre property in Kamloops, BC: an interactive
3D model of the terrain (built from a contour survey) plus the development vision and
sample site plans.

**Live site:** https://singh-gursahib.github.io/10acresProject/

## Contents
- `index.html` — the main presentation site (hero, 3D model, vision, plan gallery)
- `viewer/index.html` — a standalone full-screen 3D viewer
- `viewer/terrain.glb` — the 3D terrain model
- `assets/` — hero image and sample-plan gallery images

Everything is static. No build step or server is required; it runs directly on
GitHub Pages. The 3D model is loaded in the browser with Three.js (from a CDN).

## Enabling GitHub Pages
Settings → Pages → Build and deployment → Source: **Deploy from a branch**,
Branch: **main** / **/ (root)**. Save, wait a minute, then open the live URL above.
