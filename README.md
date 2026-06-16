# AV Room Planner

**3D AV Room Planner with DWG floor plan import** — a clean, modern tool for AV professionals.

## Features (v1.0)

- **DWG / DXF Import**
  - Drag & drop support for `.dwg` and `.dxf` files
  - One-click "Open in Autodesk Viewer" — the highest quality free viewer available
  - Clear upgrade path documented for full native parsing

- **Interactive 3D Planner**
  - Fully interactive Three.js scene with mouse/touch orbit controls
  - Pre-built conference room (24' × 18')
  - Equipment library: Projectors, Large Displays, PTZ Cameras, Ceiling Speakers
  - Add, position, and clear equipment in real time
  - Export current view as PNG

- **Modern, usable interface**
  - Dark theme optimized for technical work
  - Clean layers panel and project info
  - Keyboard shortcuts (`R` to reset, `?` for info)

## How to use

1. Open [https://digitalviper.github.io/av-room-planner](https://digitalviper.github.io/av-room-planner)
2. Drag a `.dwg` or `.dxf` file into the import box
3. Click **"Open in Autodesk Viewer"** for the best possible rendering and measurement tools
4. Use the 3D planner to lay out AV equipment on top of your floor plan concept

## Current DWG Limitations & Roadmap

**Today (v1.0):**  
We provide excellent UX around DWG files and direct integration with the free Autodesk Viewer. Full geometry parsing into the Three.js scene is not yet implemented.

**Coming soon:**
- Native browser DWG parsing using [`libredwg-web`](https://github.com/mlightcad/libredwg-web) (WebAssembly)
- Direct import of walls, layers, and dimensions into the 3D scene
- Optional deep integration with **Autodesk Platform Services (APS)** for enterprise-grade viewing + markup

## Tech Stack

- HTML + Tailwind CSS (CDN)
- Three.js r134
- Vanilla JavaScript (no build step)
- Hosted on GitHub Pages

## Local Development

Just open `index.html` in any modern browser. No build tools required.

```bash
# Or serve it locally
npx serve .
```

## Deployment

This site is automatically deployed via GitHub Pages from the `main` branch.

---

Built with ❤️ by digitalviper.