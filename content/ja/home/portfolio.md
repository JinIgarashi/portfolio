+++
# A Portfolio section showing websites and open-source software I have developed.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 45  # Order that this section will appear.

title = "ポートフォリオ"
subtitle = "これまでに開発した Web アプリケーション・オープンソースソフトウェア"

[content]
  # Page type to display (folder name under content/).
  page_type = "portfolio"

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  [[content.filter_button]]
    name = "すべて"
    tag = "*"

  [[content.filter_button]]
    name = "WebGIS"
    tag = "WebGIS"

  [[content.filter_button]]
    name = "水分野"
    tag = "Water"

  [[content.filter_button]]
    name = "ライブラリ"
    tag = "Library"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3
+++
