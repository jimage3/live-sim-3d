# live-sim-3d
Lightweight 3D live viewer for Kranker Canon.

## What it does
- Loads `version.json` and `canon-index.json` from **canon-core/artifacts**
- (Optional) Loads `zones.geojson` to draw the city block footprint
- Simple 3D scene (Three.js CDN) with OrbitControls
- Era filter & base URL picker (works with GitHub Pages)

## Quick start
1) Open `index.html` locally, or deploy with GitHub Pages
2) Set **Artifacts Base URL** (e.g. `https://<org>.github.io/canon-core/artifacts`)
3) Click **Load** → version & index shown, zone polygon rendered as a plate