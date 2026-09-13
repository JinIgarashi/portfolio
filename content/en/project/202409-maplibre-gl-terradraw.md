---
title: "maplibre-gl-terradraw & Terra Draw"
subtitle: ""
summary: "Author and maintainer of maplibre-gl-terradraw, a drawing and measuring plugin for MapLibre GL JS powered by Terra Draw."
authors: ["Jin Igarashi"]
tags: ["MapLibre", "Terra Draw", "Open Source", "JavaScript"]
categories: []
date: 2024-09-01T00:00:00+09:00
lastmod: 2026-09-13T00:00:00+09:00
weight: 2
featured: false
draft: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
---
**Period:** September 2024 – present

**Links:** [GitHub (watergis/maplibre-gl-terradraw)](https://github.com/watergis/maplibre-gl-terradraw) · [Terra Draw](https://github.com/JamesLMilner/terra-draw) · [Terra Draw workshops](https://workshops.terradraw.water-gis.com/)

## Background

For a long time, both Mapbox and MapLibre relied on [mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw) to provide drawing functionality. However, it is no longer actively maintained, and it has become increasingly difficult to use with MapLibre. [Terra Draw](https://github.com/JamesLMilner/terra-draw) is a drawing library with a unified API for most web mapping libraries (MapLibre, Mapbox, Leaflet, OpenLayers, Google Maps and ArcGIS), but integrating its full functionality into MapLibre still requires a lot of configuration.

## What I built

I developed **maplibre-gl-terradraw**, a MapLibre plugin that adds a pre-configured drawing feature with a single line of code:

```js
map.addControl(new MaplibreTerradrawControl())
```

- All Terra Draw modes (point, line, polygon, rectangle, circle, freehand, etc.) with pre-configured icons
- Selecting, editing and deleting features, and downloading drawn features
- Customizable Terra Draw options and styles
- **Measure control** to measure line distances and polygon areas, and to query elevation from raster DEM sources (MapLibre Terrain, TerrainRGB and Terrarium)

I also contribute to Terra Draw itself and maintain hands-on workshop materials for developers.

## Talks & workshops

- [FOSS4G Europe 2025 Mostar: maplibre-gl-terradraw - new drawing plugin for maplibre-gl-js](../../talk/20250718_foss4g2025/)
- [FOSS4G 2025 Auckland: Terra Draw workshop](../../talk/20251118_foss4g2025_terradraw_workshop/)
- [FOSS4G 2025 Auckland: maplibre-gl-terradraw - new drawing plugin for maplibre-gl-js](../../talk/20251119_foss4g2025_maplibre-gl-terradraw/)
- [FOSS4G 2026 Hiroshima: Terra Draw workshop](../../talk/20260831_foss4g2026_terradraw_workshop/)
- [FOSS4G 2026 Hiroshima: Terra Draw - bring drawing feature to all map applications](../../talk/20260903_foss4g2026_terradraw/)

## Tech stack

TypeScript, MapLibre GL JS, Terra Draw, Vite
