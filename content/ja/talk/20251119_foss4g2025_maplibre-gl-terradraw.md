---
title: "[FOSS4G 2025 Auckland] maplibre-gl-terradraw - new drawing plugin for maplibre-gl-js"
subtitle: ""
summary: "MapLibre向け描画プラグインmaplibre-gl-terradrawについて発表しました"
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
location: "オークランド, ニュージーランド"
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

**イベント:** [FOSS4G 2025 Auckland](https://2025.foss4g.org)（オークランド, ニュージーランド）

MapLibre向けの新しい描画プラグイン[maplibre-gl-terradraw](https://github.com/watergis/maplibre-gl-terradraw)を紹介しました。メンテナンスが止まっている[mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw)に代わる、モダンな描画プラグインです。

プラグインは[Terra Draw](https://github.com/JamesLMilner/terra-draw)をベースにMapLibre専用に設計されており、1行のコードで設定済みの描画機能を追加できます。

```js
map.addControl(new MaplibreTerradrawControl())
```

このコントロールにより、以下の機能が使えるようになります。

- ポイント、ライン、ポリゴン、矩形、円などの多様な描画モード
- 描画した地物の選択・削除・ダウンロード
- ラインの距離やポリゴンの面積の計算、ラスタDEMからの標高取得ができる**計測コントロール**

発表では主要な機能をデモし、MapLibreアプリケーションに描画機能をいかに簡単に組み込めるかを紹介しました。

発表概要は[こちらのページ](https://talks.osgeo.org/foss4g-2025/talk/FJYFLZ/)でご覧いただけます。
