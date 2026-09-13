---
title: "UNDP RAPIDA"
subtitle: ""
summary: "UNDPにて、危機への迅速な対応のための半自動地理空間評価ツール「RAPIDA」を開発しました。"
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
**期間:** 2024年11月 〜 2025年8月

**所属:** 国連開発計画（UNDP）

**リンク:** [GitHub (UNDP-Data/rapida)](https://github.com/UNDP-Data/rapida)（BSD-3-Clause）

## 概要

RAPIDAは、危機への迅速な対応のための半自動の地理空間分析ツールです。自然災害などの危機が発生した際に、厳選されたグローバルな地理空間データセットから対象地域のゾーン統計を計算し、人口・資産・経済への影響（エクスポージャー）を素早く評価します。結果はUNDP GeoHubを通じて共有でき、意思決定者がすぐに活用できます。

## 機能

- OpenStreetMapとOCHAから行政界データを取得・整備
- 対象地域について複数の要素を評価:
  - **人口:** WorldPop（constrained, UN-adjusted）
  - **建物:** Google、Microsoft、OpenStreetMapの建物フットプリントを統合
  - **送配電網:** 予測モデルによるグローバルな配電網
  - **道路:** GRIPグローバル道路データセット
  - **土地利用:** Sentinel-2画像とGoogle Dynamic Worldモデル
  - **社会経済:** 剥奪指数（Deprivation Index）、相対的富裕指数（RWI）、GDP
- UNDPのAzureストレージでのプロジェクト管理と[GeoHub](../202112-undp-geohub/)への公開
- ノートブックや可視化のためのJupyterHubとの連携
- 使いやすいコマンドラインインターフェース: `init`, `auth`, `admin`, `create`, `assess`, `list`, `download`, `upload`, `publish`, `delete`

## 技術スタック

Python, GDAL, rasterio, exactextract, GeoPandas, Click, Rich, Azure Blob Storage, JupyterHub
