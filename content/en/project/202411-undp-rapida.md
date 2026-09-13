---
title: "UNDP RAPIDA"
subtitle: ""
summary: "Developed RAPIDA, a semi-automated geospatial assessment tool for rapid crisis response at UNDP."
authors: ["Jin Igarashi"]
tags: ["GIS", "UNDP", "Python", "Open Source"]
categories: ["UNDP"]
date: 2024-11-01T00:00:00+09:00
lastmod: 2026-09-13T00:00:00+09:00
weight: 3
featured: false
draft: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
---
**Period:** November 2024 – August 2025

**Organization:** United Nations Development Programme (UNDP)

**Links:** [GitHub (UNDP-Data/rapida)](https://github.com/UNDP-Data/rapida) (BSD-3-Clause)

## Overview

RAPIDA is a semi-automated geospatial analysis tool for rapid crisis response. When a crisis such as a natural disaster happens, it quickly assesses the exposure of people, assets and the economy within an area of interest by computing zonal statistics from curated global geospatial datasets. The results can be shared through UNDP GeoHub so that decision makers can use them right away.

## Features

- Fetches and curates administrative boundaries from OpenStreetMap and OCHA
- Assesses multiple exposure components over an area of interest:
  - **Population:** WorldPop (constrained, UN-adjusted)
  - **Buildings:** merged Google, Microsoft and OpenStreetMap building footprints
  - **Electrical grid:** predictive global distribution networks
  - **Roads:** GRIP global roads dataset
  - **Land use:** Sentinel-2 imagery with the Google Dynamic World model
  - **Socioeconomic:** deprivation index, relative wealth index and GDP
- Project management on UNDP Azure storage and publishing to [GeoHub](../202112-undp-geohub/)
- Integration with JupyterHub for notebooks and visualization
- Rich command line interface: `init`, `auth`, `admin`, `create`, `assess`, `list`, `download`, `upload`, `publish`, `delete`

## Tech stack

Python, GDAL, rasterio, exactextract, GeoPandas, Click, Rich, Azure Blob Storage, JupyterHub
