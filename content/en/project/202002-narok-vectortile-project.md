---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Open Source Project for Water Vector Tile app"
subtitle: ""
summary: "This project is to develop an simple open source software to develop Mapbox Vector Tile application easily from your PostgreSQL/PostGIS"
authors: ["Jin Igarashi"]
tags: []
categories: []
date: 2020-02-01T00:00:00+09:00
lastmod: 2020-06-18T20:34:23+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

I developed a simple [open source tools](https://github.com/watergis/awesome-vector-tiles) to create and deploy vectortiles easily.

Currently, the following water services providers are using my tools.

1. [Water Supply Map for Narok Water, KENYA](https://narok.water-gis.com): since June 2020.
2. [Water Supply Map for WASAC RWSS, RWANDA](https://rural.water-gis.com): since July 2020.
3. [Water Supply Map for Nakuru Water, KENYA](https://nakuru.water-gis.com): since August 2020.

This tool is using direct SQL to create vectortiles from your PostGIS database. So, my tool can adopt any PostGIS database easily. If there is already PostGIS in your organizaiton, it is so fast to be able to host your vectorties. But please also contact me if you do not have PostGIS database yet. I will support your organization to develop PostGIS database and adopt it for vectortiles.
