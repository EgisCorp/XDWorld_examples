# XDWorld Examples

This repository contains standalone examples of the **XDWorld WebGL Engine**, designed to run directly in the browser via GitHub Pages.

Each sample demonstrates a specific feature of the XDWorld engine, such as terrain interaction, object rendering, analysis tools, measurement modes, and various visualization effects.

## 🌍 Live Demo Site

Access the published examples directly via GitHub Pages:

👉 [https://egiscorp.github.io/XDWorld_examples](https://egiscorp.github.io/XDWorld_examples)

## 📁 Directory Structure

```
XDWorld_examples/
├── analysis_measure_distance.html     # Example: 2D ground distance measurement
├── analysis_measure_altitude.html     # Example: Altitude measurement using POIs
├── analysis_measure_area.html         # Example: Area measurement over terrain
├── ...                                # Many more examples by feature category
├── worker/                            # WebWorker scripts for multithreaded processing
└── assets/                            # (optional) thumbnails, icons, or data files
```

## 📦 Requirements

No installation is needed. Just open the `.html` files in a browser.

If you’re hosting your own, make sure:
- The `XDWorldEM.js` and related WASM/worker files are loaded from CDN or locally provided.

## 🔧 Example Features

| Category        | Description                            |
|----------------|----------------------------------------|
| Analysis        | Shadow simulation, terrain slicing, viewshed, etc. |
| Measurement     | Altitude, distance, area, radius      |
| Camera          | Camera movement, tracking, quake, FOV |
| Object Rendering| 3D tiles, GeoJSON, billboard, pipe, video overlays |
| Layer Control   | Base layers, WMS/WMTS/WFS loading     |
| Environmental   | Fog, rain, snow, wind simulation      |

## 🧠 About XDWorld Engine

XDWorld is a high-performance WebGL 3D engine specialized for spatial data visualization and real-time geospatial analysis. It supports terrain rendering, massive 3D object display, interactive tools, and analysis capabilities directly within the browser.

This repository aims to provide reproducible and minimal examples to demonstrate what the engine can do.

## 🤖 GPT / AI Accessibility

This repository is **publicly crawlable**, enabling LLMs such as ChatGPT to:
- Understand the XDWorld engine structure and API usage
- Reference standalone samples with real code
- Learn how terrain, camera, and object APIs are used

---

For questions or contributions, feel free to open an issue or contact us via [https://github.com/EgisCorp/XDWorld/issues](https://github.com/EgisCorp/XDWorld/issues).