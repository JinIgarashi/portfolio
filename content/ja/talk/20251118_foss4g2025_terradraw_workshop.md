---
title: "[FOSS4G 2025 Auckland] Terra Draw - cross-platform drawing library for all map applications Workshop"
subtitle: ""
summary: "Terra Drawとmaplibre-gl-terradrawの3時間のハンズオンワークショップを実施しました"
authors: ["Jin Igarashi"]
tags: ["FOSS4G"]
categories: []
date: 2025-11-18T09:00:00+13:00
date_end: 2025-11-18T12:00:00+13:00
all_day: false
lastmod: 2026-09-13T00:00:00+09:00
featured: false
draft: false

event: "FOSS4G 2025 Auckland"
event_url: "https://2025.foss4g.org"
location: "オークランド, ニュージーランド"
url_slides: "https://talks.osgeo.org/media/foss4g-2025/submissions/7S9CLN/resources/workshop_introduction_1YiaNuT.pdf"
links:
- name: "ワークショップ教材"
  url: "https://workshops.terradraw.water-gis.com/workshops/foss4g2025/"
- name: "ワークショップテンプレート"
  url: "https://github.com/watergis/terradraw-workshop-template"
- name: "Terra Draw"
  url: "https://github.com/JamesLMilner/terra-draw"

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: ["202409-maplibre-gl-terradraw"]
---

**イベント:** [FOSS4G 2025 Auckland](https://2025.foss4g.org)（オークランド, ニュージーランド）

[Terra Draw](https://github.com/JamesLMilner/terra-draw)は、MapLibre、Leaflet、OpenLayers、Mapbox、Google Maps、ArcGISといった様々な地図ライブラリで使える描画ライブラリです。統一されたAPIを備えているため、異なるWeb地図ライブラリでも同じコードで描画機能を実装できます。

この3時間のワークショップは2部構成で実施しました。

1. **イントロダクション:** Terra Drawとは何か、地図アプリケーションで何ができるかを紹介
2. **ハンズオン:** MapLibre GL JSとTerra Drawを組み合わせたコーディング演習
   - Terra Drawのインストールとセットアップ
   - レイヤーのスタイリングやイベントなどの応用機能
   - 1行で設定済みの描画コントロールを追加できる[maplibre-gl-terradraw](https://github.com/watergis/maplibre-gl-terradraw)プラグイン

他の地図ライブラリでのTerra Drawの使い方も紹介し、プラットフォームを問わず活用できることを示しました。参加者はNode.js v22 LTSとVSCodeをインストールしたノートPCを持参して参加しました。

- ワークショップ教材: [workshops.terradraw.water-gis.com](https://workshops.terradraw.water-gis.com/)
- サンプルコードとテンプレート: [watergis/terradraw-workshop-template](https://github.com/watergis/terradraw-workshop-template)

発表概要は[こちらのページ](https://talks.osgeo.org/foss4g-2025/talk/7S9CLN/)でご覧いただけます。
