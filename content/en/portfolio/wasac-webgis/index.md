---
title: "WASAC Rural Water WebGIS"
subtitle: ""
summary: "Nationwide WebGIS of rural water supply systems for WASAC (Water and Sanitation Corporation) in Rwanda."
authors: ["Jin Igarashi"]
tags: ["WebGIS", "Water", "Rwanda"]
categories: []
date: 2020-06-01T00:00:00+09:00
lastmod: 2026-09-27T00:00:00+09:00
weight: 3
featured: false
draft: false

# Link buttons shown on the portfolio card and page.
links:
  - name: Website
    url: https://rural.water-gis.com
    icon_pack: fas
    icon: globe
  - name: GitHub
    url: https://github.com/WASAC
    icon_pack: fab
    icon: github

# Thumbnail shared by all languages (static/images/portfolios/).
thumbnail: images/portfolios/wasac-webgis.webp

projects: []
---

A WebGIS that publishes the nationwide rural water supply data of Rwanda, which was mapped with Rwandan colleagues during the JICA RWASOM project. The PostGIS database is converted to vector tiles hosted on GitHub Pages, together with 10 m terrain RGB tiles and administrative boundaries.

**Tech stack:** PostgreSQL/PostGIS, QGIS/QField, vector tiles, terrain RGB, MapLibre GL JS, GitHub Pages

**Related:** [RWASOM project](../../project/201806-rwasom/) · [FOSS4G 2021: QGIS, QField and Vector Tiles for rural water supply management in Rwanda](../../talk/20211001_foss4g2021_wasac/)
