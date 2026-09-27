---
title: "WASAC Rural Water WebGIS"
subtitle: ""
summary: "ルワンダ水衛生公社（WASAC）向け、全国の地方給水施設を可視化する WebGIS。"
authors: ["me"]
tags: ["WebGIS", "Water", "Rwanda"]
categories: []
date: 2020-06-01T00:00:00+09:00
lastmod: 2026-09-27T00:00:00+09:00
weight: 3
featured: false
draft: false

links:
  - name: Webサイト
    url: https://rural.water-gis.com
    icon: hero/globe-alt
  - name: GitHub
    url: https://github.com/WASAC
    icon: brands/github

projects: []
---

JICA RWASOM プロジェクトでルワンダの同僚と共に整備した、全国の地方給水施設データを公開する WebGIS です。PostGIS のデータをベクトルタイル化して GitHub Pages でホストし、10m 解像度の Terrain RGB タイルや行政界も合わせて配信しています。

**技術スタック:** PostgreSQL/PostGIS, QGIS/QField, ベクトルタイル, Terrain RGB, MapLibre GL JS, GitHub Pages

**関連:** [RWASOM プロジェクト](../../projects/201806-rwasom/) · [FOSS4G 2021: QGIS, QField and Vector Tiles for rural water supply management in Rwanda](../../events/20211001_foss4g2021_wasac/)
