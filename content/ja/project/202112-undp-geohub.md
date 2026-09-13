---
title: "UNDP GeoHub"
subtitle: ""
summary: "政策立案者向けの地理空間データの可視化・分析・共有を行うUNDPのオープンソースプラットフォーム「GeoHub」を開発しました。"
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
**期間:** 2021年12月 〜 2025年8月

**所属:** 国連開発計画（UNDP）政策・プログラム支援局 SDG Integration Team

**役割:** GISコンサルタント → フルスタックGISデベロッパー

**リンク:** [GeoHub](https://geohub.data.undp.org) · [GitHub (UNDP-Data/geohub)](https://github.com/UNDP-Data/geohub)

## 背景

UNDPはデータドリブンな組織への変革を加速するために組織全体のデータ戦略を策定しており、その中で地理空間データは重要な役割を担っています。しかし、各国事務所に分散したデータのサイロ化、相互運用性の欠如、インフラやノウハウの不足などにより、地理空間データの大規模な活用は進んでいませんでした。GeoHubはこれらの課題を解決するため、Data Futures Exchange（DFx）の一部として開発されました。

## GeoHubとは

GeoHubは、開発分野の業務を支援するための地理空間データとサービスの統合的なエコシステムです。GISの専門知識を持たないUNDP職員や政策立案者が、以下のことを簡単に行えます。

- 衛星画像や時空間モデルデータを含む多様なデータセットの検索・可視化・ダウンロード
- データアップロードパイプラインによる独自データの登録
- 動的な統計の算出やラスタ解析の実行
- 地図の作成とコミュニティへの共有

## アーキテクチャ

- **フロントエンド:** SvelteKitとMapLibre GL JSによるWebアプリケーション
- **バックエンド:** Azure Kubernetes Service（AKS）上にデプロイしたPostgreSQL/PostGIS、titiler、pg_tileservなどのFOSS4Gソフトウェア
- **クラウド:** Azure App Service、Blob Storage、PubSub
- **データ:** Cloud Optimized GeoTIFF、ベクタータイル、STACカタログ
- ソースコードはすべてオープンソースライセンスでGitHubに公開

## 主に開発した機能

- GeoHubの各ページへ誘導するランディングページ
- ソーシャルログイン（GitHub認証、UN B2C認証）
- データアップロードパイプライン
- データセット・地図のユーザー権限管理
- MapLibreによるデータ可視化のUI/UX改善
- ラスタ解析機能（titilerアルゴリズム）
- 保存したMapLibreスタイルから静的地図画像を生成するStatic Image API

## 関連する発表

- [FOSS4G 2023 Prizren: UNDP's one stop shop for cloud based geospatial data visualisation and analytical tool](../../talk/20230629_foss4g2023_undpgeohub/)
- [FOSS4G 2023 Prizren: Development of maplibre applications in sveltekit](../../talk/20230628_foss4g2023_svelte/)
- [FOSS4G Europe 2024 Tartu: Leave no one behind - UNDP GeoHub](../../talk/20240705_foss4g2024/)

GeoHubと連携する危機評価ツール[RAPIDA](../202411-undp-rapida/)もご覧ください。

## スキル

MapLibre, Mapbox, Svelte/SvelteKit, Node.js (JavaScript/TypeScript), Python, PostgreSQL/PostGIS, titiler, pg_tileserv, STAC, Azure (AKS, App Service, Blob Storage, PubSub)
