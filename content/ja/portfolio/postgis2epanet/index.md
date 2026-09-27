---
title: "postgis2epanet"
subtitle: ""
summary: "PostGIS データベースからルワンダ全国の地方給水システムの EPANET INP ファイルを生成するツール。"
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

WASAC 地方給水部向けに開発したツールです。PostGIS の管路ネットワークをルワンダ全国の給水システム・郡ごとに EPANET INP ファイル（およびシェープファイル）として出力し、必要に応じて DEM から標高を付与します。エンジニアがすぐに水理解析を始められるようにしました。

**技術スタック:** Python, psycopg2, Shapely, PyShp, Docker, EPANET
