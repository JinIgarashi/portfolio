---
title: "maplibre-gl-terradraw & Terra Draw"
subtitle: ""
summary: "Terra Drawを用いたMapLibre GL JS向けの描画・計測プラグイン「maplibre-gl-terradraw」を開発・メンテナンスしています。"
authors: ["Jin Igarashi"]
tags: ["MapLibre", "Terra Draw", "Open Source", "JavaScript"]
categories: []
date: 2024-09-01T00:00:00+09:00
lastmod: 2026-09-13T00:00:00+09:00
weight: 2
featured: false
draft: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
---
**期間:** 2024年9月 〜 現在

**リンク:** [GitHub (watergis/maplibre-gl-terradraw)](https://github.com/watergis/maplibre-gl-terradraw) · [Terra Draw](https://github.com/JamesLMilner/terra-draw) · [Terra Drawワークショップ](https://workshops.terradraw.water-gis.com/)

## 背景

MapboxとMapLibreでは長い間、描画機能に[mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw)が使われてきました。しかし現在は活発にメンテナンスされておらず、MapLibreで使うことが難しくなってきています。[Terra Draw](https://github.com/JamesLMilner/terra-draw)は主要なWeb地図ライブラリ（MapLibre、Mapbox、Leaflet、OpenLayers、Google Maps、ArcGIS）に対して統一されたAPIを持つ描画ライブラリですが、その機能をMapLibreで最大限に活用するには多くの設定が必要です。

## 開発したもの

1行のコードで設定済みの描画機能を追加できるMapLibreプラグイン **maplibre-gl-terradraw** を開発しました。

```js
map.addControl(new MaplibreTerradrawControl())
```

- アイコン設定済みのTerra Drawの全描画モード（ポイント、ライン、ポリゴン、矩形、円、フリーハンドなど）
- 地物の選択・編集・削除、描画した地物のダウンロード
- Terra Drawのオプションやスタイルのカスタマイズ
- **計測コントロール**: ラインの距離やポリゴンの面積の計測、ラスタDEM（MapLibre Terrain、TerrainRGB、Terrarium）からの標高取得

Terra Draw本体へのコントリビュートや、開発者向けハンズオンワークショップ教材のメンテナンスも行っています。

## 発表・ワークショップ

- [FOSS4G Europe 2025 Mostar: maplibre-gl-terradraw - new drawing plugin for maplibre-gl-js](../../talk/20250718_foss4g2025/)
- [FOSS4G 2025 Auckland: Terra Drawワークショップ](../../talk/20251118_foss4g2025_terradraw_workshop/)
- [FOSS4G 2025 Auckland: maplibre-gl-terradraw - new drawing plugin for maplibre-gl-js](../../talk/20251119_foss4g2025_maplibre-gl-terradraw/)
- [FOSS4G 2026 Hiroshima: Terra Drawワークショップ](../../talk/20260831_foss4g2026_terradraw_workshop/)
- [FOSS4G 2026 Hiroshima: Terra Draw - bring drawing feature to all map applications](../../talk/20260903_foss4g2026_terradraw/)

## 技術スタック

TypeScript, MapLibre GL JS, Terra Draw, Vite
