---
title: "[FOSS4G 2026 Hiroshima] Terra Draw - bring drawing feature to all map applications"
subtitle: ""
summary: "Presented the latest state of Terra Draw and maplibre-gl-terradraw"
authors: ["Jin Igarashi"]
tags: ["FOSS4G"]
categories: []
date: 2026-09-03T14:30:00+09:00
date_end: 2026-09-03T15:00:00+09:00
all_day: false
lastmod: 2026-09-13T00:00:00+09:00
featured: false
draft: false

event: "FOSS4G 2026 Hiroshima"
event_url: "https://2026.foss4g.org"
location: "Hiroshima, Japan"
url_slides: "https://workshops.terradraw.water-gis.com/presentations/foss4g-2026-slides_slide"
links:
- name: "Terra Draw"
  url: "https://github.com/JamesLMilner/terra-draw"
- name: "maplibre-gl-terradraw"
  url: "https://github.com/watergis/maplibre-gl-terradraw"

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: ["202409-maplibre-gl-terradraw"]
---

**Event:** [FOSS4G 2026 Hiroshima](https://2026.foss4g.org), Hiroshima, Japan

[Terra Draw](https://github.com/JamesLMilner/terra-draw) is a drawing library with unified interfaces for most mapping libraries. This talk updated the current state of Terra Draw and [maplibre-gl-terradraw](https://github.com/watergis/maplibre-gl-terradraw).

Implementing drawing functionality across diverse mapping libraries is complex, because each library has its own API. Terra Draw, created four years ago, standardizes drawing capabilities for major libraries including Leaflet, OpenLayers, Google Maps, Mapbox GL JS and MapLibre GL JS.

The talk covered:

- fundamental drawing modes such as points, lines and polygons
- advanced features such as snapping and rotation
- **maplibre-gl-terradraw**, a plugin I maintain, which enables straightforward integration of sophisticated drawing tools into MapLibre applications

the abstract is available [this page](https://talks.osgeo.org/foss4g-2026/talk/SHKRZZ/)
