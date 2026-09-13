---
title: "UNDP GeoHub"
subtitle: ""
summary: "Developed GeoHub, UNDP's open-source platform for geospatial data visualization, analysis and sharing for policymakers."
authors: ["Jin Igarashi"]
tags: ["GIS", "UNDP", "MapLibre", "SvelteKit", "Open Source"]
categories: ["UNDP"]
date: 2021-12-01T00:00:00+09:00
lastmod: 2026-09-13T00:00:00+09:00
featured: false
draft: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
---
**Period:** December 2021 – August 2025

**Organization:** United Nations Development Programme (UNDP), SDG Integration Team, Bureau for Policy and Programme Support

**Role:** GIS Consultant → Full Stack GIS Developer

**Links:** [GeoHub](https://geohub.data.undp.org) · [GitHub (UNDP-Data/geohub)](https://github.com/UNDP-Data/geohub)

## Background

UNDP has developed a corporate data strategy to accelerate its transformation into a data-driven organization, and geospatial data plays an important role in it. However, the large-scale adoption of geospatial data had been obstructed by data silos across country offices, lack of interoperability, and limited infrastructure and know-how. GeoHub was developed as a part of the Data Futures Exchange (DFx) to solve these issues.

## What is GeoHub?

GeoHub is a centralized ecosystem of geospatial data and services to support development work. It allows users without geospatial skills — UNDP staff and policymakers — to:

- search, visualize and download a wide array of datasets, including satellite imagery and spatio-temporal model data
- upload their own datasets through a data upload pipeline
- compute dynamic statistics and run raster analytics
- create maps and share them with the community easily

## Architecture

- **Frontend:** SvelteKit and MapLibre GL JS web applications
- **Backend:** PostgreSQL/PostGIS, titiler, pg_tileserv and other FOSS4G software deployed on Azure Kubernetes Service (AKS)
- **Cloud:** Azure App Service, Blob Storage, PubSub
- **Data:** Cloud Optimized GeoTIFF, vector tiles and STAC catalogues
- All source code is published on GitHub under an open-source license

## Main features I developed

- Landing page to direct users to each part of GeoHub
- Social login (GitHub authentication and UN B2C authentication)
- Data upload pipeline
- User permission management for datasets and maps
- UI/UX improvements for data visualization with MapLibre
- Raster analytical features (titiler algorithms)
- Static image API to generate static map images from a saved MapLibre style

## Related talks

- [FOSS4G 2023 Prizren: UNDP's one stop shop for cloud based geospatial data visualisation and analytical tool](../../talk/20230629_foss4g2023_undpgeohub/)
- [FOSS4G 2023 Prizren: Development of maplibre applications in sveltekit](../../talk/20230628_foss4g2023_svelte/)
- [FOSS4G Europe 2024 Tartu: Leave no one behind - UNDP GeoHub](../../talk/20240705_foss4g2024/)

See also [RAPIDA](../202411-undp-rapida/), a crisis assessment tool integrated with GeoHub.

## Skills

MapLibre, Mapbox, Svelte/SvelteKit, Node.js (JavaScript/TypeScript), Python, PostgreSQL/PostGIS, titiler, pg_tileserv, STAC, Azure (AKS, App Service, Blob Storage, PubSub)
