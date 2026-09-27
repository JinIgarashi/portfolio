---
title: "postgis2epanet"
subtitle: ""
summary: "Generates EPANET INP files for all rural water supply systems in Rwanda from a PostGIS database."
authors: ["me"]
tags: ["Library", "Water", "Rwanda"]
categories: []
date: 2019-06-01T00:00:00+09:00
lastmod: 2026-09-27T00:00:00+09:00
weight: 6
featured: false
draft: false

links:
  - name: GitHub
    url: https://github.com/WASAC/postgis2epanet
    icon: brands/github

projects: []
---

A tool designed for the RWSS department of WASAC. It exports the water pipeline network from PostGIS to EPANET INP files (and Shapefiles) for each water supply system and district across Rwanda, optionally updating node elevations from a DEM, so that engineers can start hydraulic analysis immediately.

**Tech stack:** Python, psycopg2, Shapely, PyShp, Docker, EPANET
