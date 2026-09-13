---
title: "[FOSS4G 2025 Auckland] maplibre-gl-terradraw - new drawing plugin for maplibre-gl-js"
subtitle: ""
summary: "Presented a talk about maplibre-gl-terradraw, a drawing plugin for MapLibre"
authors: ["Jin Igarashi"]
tags: ["FOSS4G"]
categories: []
date: 2025-11-19T16:00:00+13:00
date_end: 2025-11-19T16:25:00+13:00
all_day: false
lastmod: 2026-09-13T00:00:00+09:00
featured: false
draft: false

event: "FOSS4G 2025 Auckland"
event_url: "https://2025.foss4g.org"
location: "Auckland, New Zealand"
url_slides: "https://talks.osgeo.org/media/foss4g-2025/submissions/FJYFLZ/resources/20251119_maplibre-gl-terradraw_-_new_drawing_pl_AskCXS0.pdf"
links:
- name: "GitHub"
  url: "https://github.com/watergis/maplibre-gl-terradraw"

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: ["202409-maplibre-gl-terradraw"]
---

**Event:** [FOSS4G 2025 Auckland](https://2025.foss4g.org), Auckland, New Zealand

This talk introduced [maplibre-gl-terradraw](https://github.com/watergis/maplibre-gl-terradraw), a new drawing plugin for MapLibre and a modern replacement for the unmaintained [mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw).

The plugin is built on [Terra Draw](https://github.com/JamesLMilner/terra-draw) and designed specifically for MapLibre, providing a pre-configured drawing feature with a single line of code:

```js
map.addControl(new MaplibreTerradrawControl())
```

With this control, users get:

- multiple drawing modes — point, line, polygon, rectangle, circle and more
- selecting, deleting and downloading drawn features
- a **measure control** to calculate the distance of lines and the area of polygons, and to query elevation from raster DEM sources

In the talk, I demonstrated the core functionalities and how easily drawing features can be integrated into MapLibre applications.

the abstract is available [this page](https://talks.osgeo.org/foss4g-2025/talk/FJYFLZ/)
