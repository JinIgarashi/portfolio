---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a file name within `data/authors/`)
      username: me
      text: ''
      button:
        text: CVをダウンロード
        url: https://jin-igarashi.me/files/cv_jin_igarashi.pdf
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: resume-skills
    id: skills
    content:
      title: スキル
      username: me
    design:
      columns: 3
  - block: resume-experience
    id: experience
    content:
      title: 職歴
      username: me
    design:
      date_format: 'Jan 2006'
      is_education_first: false
  - block: portfolio
    id: portfolio
    content:
      title: ポートフォリオ
      subtitle: これまでに開発したWebアプリケーションとオープンソースソフトウェア
      filters:
        folders:
          - portfolio
      sort_by: Weight
      sort_ascending: true
      buttons:
        - name: すべて
          tag: '*'
        - name: WebGIS
          tag: WebGIS
        - name: Water
          tag: Water
        - name: ライブラリ
          tag: Library
      default_button_index: 0
    design:
      columns: 3
  - block: collection
    id: projects
    content:
      title: プロジェクト
      count: 0
      filters:
        folders:
          - projects
    design:
      view: date-title-summary
  - block: collection
    id: talks
    content:
      title: 講演
      count: 8
      filters:
        folders:
          - events
    design:
      view: date-title-summary
  - block: collection
    id: publications
    content:
      title: 執筆活動
      count: 5
      filters:
        folders:
          - publications
    design:
      view: date-title-summary
  - block: resume-awards
    id: accomplishments
    content:
      title: 資格・修了証
      username: me
    design:
      date_format: 'Jan 2006'
---
