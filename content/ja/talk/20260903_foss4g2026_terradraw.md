---
title: "[FOSS4G 2026 Hiroshima] Terra Draw - bring drawing feature to all map applications"
subtitle: ""
summary: "Terra Drawとmaplibre-gl-terradrawの最新状況について発表しました"
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
location: "広島, 日本"
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

**イベント:** [FOSS4G 2026 Hiroshima](https://2026.foss4g.org)（広島, 日本）

[Terra Draw](https://github.com/JamesLMilner/terra-draw)は、主要な地図ライブラリに対して統一されたインターフェースを持つ描画ライブラリです。本発表では、Terra Drawと[maplibre-gl-terradraw](https://github.com/watergis/maplibre-gl-terradraw)の最新状況を紹介しました。

地図ライブラリごとにAPIが異なるため、様々なライブラリで描画機能を実装するのは複雑です。4年前に誕生したTerra Drawは、Leaflet、OpenLayers、Google Maps、Mapbox GL JS、MapLibre GL JSなどの主要ライブラリの描画機能を標準化しています。

発表内容:

- ポイント、ライン、ポリゴンなどの基本的な描画モード
- スナップや回転などの応用機能
- 私がメンテナンスしている、MapLibreアプリケーションに高度な描画ツールを簡単に組み込めるプラグイン **maplibre-gl-terradraw**

発表概要は[こちらのページ](https://talks.osgeo.org/foss4g-2026/talk/SHKRZZ/)でご覧いただけます。
