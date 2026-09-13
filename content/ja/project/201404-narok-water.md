---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ナロック水道局でのGISプロジェクト"
subtitle: ""
summary: "JICA青年海外協力隊として、ケニア・ナロックで約300kmの配水管網のマッピング、料金システムと連携したGIS/WebGISの構築、無収水対策を行いました。"
authors: ["Jin Igarashi"]
tags: ["GIS","Water", "Kenya"]
categories: ["JICA", "Volunteer"]
date: 2014-04-01T08:45:17+09:00
lastmod: 2026-09-13T00:00:00+09:00
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

**期間:** 2014年4月 〜 2016年9月

**配属先:** Narok Water and Sewerage Services Co., Ltd.（NARWASSCO：ナロック上下水道公社）, ケニア

**役割:** GISスペシャリスト（JICA青年海外協力隊）

## 背景

ナロック上下水道公社は、ケニアのナロックおよびオロルルンガの町に給水する水道事業体です。東アフリカの多くの水道事業体と同様に無収水（NRW）率が高く、配水管網や顧客の正確な地図も整備されていませんでした。国際協力機構（JICA）の青年海外協力隊のGISスペシャリストとして派遣され、水道資産管理と無収水対策のためのGISの導入を行いました。

## 活動内容

- **配水管網のマッピング:** Trimble GPS、ArcPad、QGISを用いて、ナロックとオロルルンガの配水管網全体（総延長約300km）をマッピングしました。
- **GISデータベースとWebGIS:** PostGIS、MapServer、Leafletを用いてGISデータベースとWebGISを設計・開発しました。料金システムと連携し、料金徴収の改善に貢献しています。
- **無収水対策:** 無収水の分析・削減のためにDMA（District Metered Area：配水ブロック）を作成しました。
- **人材育成:** ケニア人の同僚に技術移転を行うための研修を実施しました。構築したGISは現在も継続して活用されています。
- **他の水道事業体へのコンサルティング:** ケニア国内の7つの水道事業体（Nyeri Water、Kabarnet Water、Kapsabet Water、Nakuru Water、Nakuru Rural Water、Naivasha Water、Mavoko Water）に対し、GIS業務のコンサルティングを行いました。

## その後

帰国後もボランティアとしてナロック上下水道公社との個人的なパートナーシップを続けています。GISはその後[オープンソースのベクタータイル](../202002-narok-vectortile-project/)（[narok.water-gis.com](https://narok.water-gis.com)）で刷新され、活動の成果はFOSS4G 2019 BucharestやFOSS4G 2021で発表しました。

- [FOSS4G 2019: ケニア・ナロック水道公社の無収水管理の事例](../../talk/20190828_foss4g2019_kenya/)
- [FOSS4G 2021: 無収水に対するFOSS4G活用のインパクト](../../talk/20211001_foss4g2021_nanyuki/)

## スキル

水インフラのデータ収集, WebGIS, PostgreSQL/PostGIS, MapServer, Leaflet, QGIS, EPANET
