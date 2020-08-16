---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "水道局向けベクタータイルマップオープンソースプロジェクト"
subtitle: ""
summary: "PostgreSQL/PostGISのデータから簡単にMapbox Vector Tileアプリを作成するためのオープンソースソフトウェアを開発するプロジェクトです"
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

ベクタータイルを簡単に作成し、ホストできる[オープンソースのツール](https://github.com/watergis/awesome-vector-tiles)を開発しました。

現在時点で、以下の３つの水道事業体でこのツールは使用されています。

1. [Water Supply Map for Narok Water, KENYA](https://narok.water-gis.com): since June 2020.
2. [Water Supply Map for WASAC RWSS, RWANDA](https://rural.water-gis.com): since July 2020.
3. [Water Supply Map for Nakuru Water, KENYA](https://nakuru.water-gis.com): since August 2020.

このツールはSQLを使用してダイレクトにPostGISからベクタータイルを作成しますので、あらゆるデザインのPostGISに容易に適用できます。もし既にPostGISを使用している場合は迅速に開発に着手できます。仮にデータベースをまだお持ちでない場合でもご相談いただければ、データベースの設計とベクタータイルへの設定をサポートさせていただきます。
