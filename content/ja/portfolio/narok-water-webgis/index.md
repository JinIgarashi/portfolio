---
title: "Narok Water WebGIS"
subtitle: ""
summary: "ケニア・ナロク上下水道公社（NARWASSCO）の給水ネットワーク WebGIS。"
authors: ["me"]
tags: ["WebGIS", "Water", "Kenya"]
categories: []
date: 2014-09-01T00:00:00+09:00
lastmod: 2026-09-27T00:00:00+09:00
weight: 1
featured: false
draft: false

links:
  - name: Webサイト
    url: https://maps.narwassco.co.ke
    icon: hero/globe-alt
  - name: GitHub
    url: https://github.com/narwassco
    icon: brands/github

projects: []
---

JICA 海外協力隊として赴任して以来、開発・運用を続けているナロク上下水道公社の WebGIS です。約300km の配水管網、顧客、DMA を可視化し、資産管理や無収水対策に日常的に使われています。2014年に OpenLayers で開発を始め、2015年に Leaflet へ移行し、その後オープンソースのベクトルタイルと MapLibre GL JS で刷新しました。

**技術スタック:** PostgreSQL/PostGIS, ベクトルタイル, MapLibre GL JS, SvelteKit, GitHub Pages

**関連:** [ナロク上下水道公社の GIS プロジェクト](../../projects/201404-narok-water/) · [水道ベクトルタイルアプリのオープンソースプロジェクト](../../projects/202002-narok-vectortile-project/)
