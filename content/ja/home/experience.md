+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 23  # Order that this section will appear.

title = "職歴"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "2006年1月"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "ソフトウェアエンジニア"
  company = "Fracta"
  company_url = "https://fracta-jp.com/"
  company_logo = "fracta"
  location = "リモート（日本から勤務）"
  date_start = "2025-09-01"
  date_end = ""
  description = """
Fractaは、人工知能（AI）を活用して上下水道管路の劣化リスクを評価し、管路の維持管理を支援するサービスを、主にアメリカと日本の水道事業体向けに提供しているソフトウェア企業です。

- エンジニアチームに所属し、フルスタックのソフトウェアエンジニアとして勤務
- フロントエンドからバックエンド、データベースまで、新機能の開発、バグ修正、システムの保守を担当
- 上下水道事業体向けの地図を中心としたユーザーインターフェースの開発

**スキル:** Mapbox, Node.js (JavaScript), Python, Vue.js, Django, PostgreSQL/PostGIS, AWS
"""

[[experience]]
  title = "フルスタックGISデベロッパー"
  company = "国連開発計画（UNDP）"
  company_url = "https://www.undp.org"
  company_logo = "undp"
  location = "ニューヨーク（イギリス/日本からリモート勤務）"
  date_start = "2021-12-01"
  date_end = "2025-08-31"
  description = """
UNDP政策・プログラム支援局（Bureau for Policy and Programme Support）のSDG Integration Teamにて、Data Futures Exchange（DFx）の一部である[UNDP GeoHub](https://geohub.data.undp.org)の開発を担当しました。2024年10月まではイギリスから、2024年11月からは日本からリモートで勤務しました。

- GISの専門知識を持たないUNDP職員や政策立案者向けに、高度なデータ可視化・分析・共有ツールを提供するオープンソースソフトウェア「GeoHub」を開発
- SvelteKitとMapLibreによるフロントエンド、およびAzure Kubernetes Service上で稼働するFOSS4Gのバックエンド（PostgreSQL/PostGIS, titiler, pg_tileserv）を構築
- データアップロードパイプライン、データセット・地図の権限管理、ソーシャルログイン、ラスタ解析機能（titilerアルゴリズム）、STAC連携、静的地図画像APIなどを実装
- 災害・危機への迅速な対応のための半自動地理空間評価ツール[RAPIDA](https://github.com/UNDP-Data/rapida)を開発（2024年11月〜2025年8月）
- ソースコードはすべてオープンソースライセンスでGitHubに公開し、FOSS4G 2023およびFOSS4G Europe 2024で発表

契約の履歴:

- 個人コンサルタント – GISコンサルタント（パートタイム）2021年12月〜2022年9月
- IPSA-9短期 – GIS Developer（フルタイム）2022年9月〜2023年7月
- IPSA-9 – フルスタックGIS Developer（フルタイム）2023年8月〜2025年8月

**スキル:** MapLibre, Mapbox, Node.js (JavaScript), Python, Svelte/SvelteKit, PostgreSQL/PostGIS, titiler, pg_tileserv, STAC, Azure (App Service, Blob Storage, PubSub, Kubernetes など)
"""

[[experience]]
  title = "ソフトウェアエンジニア"
  company = "株式会社Geolonia"
  company_url = "https://geolonia.com"
  company_logo = "geolonia"
  location = "日本（リモート）"
  date_start = "2021-08-01"
  date_end = "2022-03-31"
  description = """
非常勤・リモートでオープンソースのGISアプリケーション開発に従事しました。

- オープンな逆ジオコーディングのオープンソースソフトウェアの開発
- MapLibreの地図スタイルを作成・管理するCLIツール[unit/charites](https://github.com/unvt/charites)の開発

**スキル:** MapLibre, ジオコーディング, 逆ジオコーディング, 地図スタイリング
"""

[[experience]]
  title = "ソフトウェアエンジニア"
  company = "株式会社オーシャンアイズ"
  company_url = "https://oceaneyes.co.jp"
  location = "日本（リモート）"
  date_start = "2021-06-01"
  date_end = "2021-11-30"
  description = """
フリーランスとして、既存のWebGISシステムの改善と新機能の開発を行いました。

- Vue.js上の地図をLeafletからMapbox GL JSへ移行
- Webサイトの様々な新機能を開発
- ソースコードを容易かつ持続的に管理するためのCI/CDを構築

**スキル:** Node.js (JavaScript), Mapbox, Leaflet, Vue.js
"""

[[experience]]
  title = "ソフトウェアエンジニア"
  company = "株式会社MIERUNE"
  company_url = "https://mierune.co.jp"
  company_logo = "mierune"
  location = "北海道, 日本"
  date_start = "2020-10-01"
  date_end = "2021-08-15"
  description = """
GISスペシャリストとして、FOSS4G（Free & Open Source Software for Geospatial）を活用したWebGISシステムの開発を行いました。

- オープンソースの地理空間ソフトウェアを用いた受託WebGISアプリケーションの開発
- Photon（オープンソースのジオコーダー）とElasticsearchを用いたジオコーディングサービスの構築
- Djangoによるバックエンド開発とクラウドへのデプロイ
- オープンソースGISのコミュニティ活動への参加

**スキル:** AWS, Google Cloud, Kubernetes, ジオコーディング, Elasticsearch, Django, Python
"""

[[experience]]
  title = "ソフトウェアエンジニア"
  company = "株式会社ONE COMPATH（ワン・コンパス）"
  company_url = "https://onecompath.com"
  location = "東京, 日本"
  date_start = "2020-01-17"
  date_end = "2020-09-30"
  description = """
日本で最も利用されているWeb地図サービスの一つである「マピオン」の開発・運用を担当しました。

- Amazon Web Services（AWS）上でMapbox Vector TilesとMapServerを用いた地図配信システムの開発と運用改善
- PostgreSQL/PostGISによる地図データの管理

**スキル:** AWS, Mapbox, MapServer, PostgreSQL/PostGIS
"""

[[experience]]
  title = "開発コンサルタント"
  company = "国際航業株式会社"
  company_url = "https://www.kkc.co.jp"
  company_logo = "kkc"
  location = "東京, 日本"
  date_start = "2017-04-01"
  date_end = "2019-12-31"
  description = """
国際協力機構（JICA）の以下のODA案件に従事しました。

- [ルワンダ国地方給水運営維持管理能力強化プロジェクト（RWASOM）](project/201806-rwasom/)（2018年6月〜2019年12月）
- [タイ王国GNSSシステム開発のための実験フィールド整備に係る調査](project/201811-thai_cors/)（2018年11月〜2019年11月）
- [ルワンダ国キガリ市ンゾベ-ントラ幹線送水管強化計画準備調査](project/201710-nzove-ntora/)（2017年10月〜2018年11月）

RWASOMプロジェクトでは、FOSS4Gアプリケーションを用いたデータ収集・データ共有の研修を実施し、地方給水管理のためのGISデータベースとデータ共有プラットフォームを設計・構築しました。ルワンダ人の同僚と協力し、全国すべての給水システムのマッピングを完了させました。システムにはPostGIS, Lizmap/QGIS Server, QGIS Desktop, QField, Garmin GPSを使用しています。

**スキル:** 地理空間データ収集, EPANET, 給水, 水インフラの設計・計画, QGIS, PostGIS
"""

[[experience]]
  title = "GISスペシャリスト（青年海外協力隊）"
  company = "NAROK WATER AND SEWERAGE SERVICES CO., LTD."
  company_url = "https://www.narwassco.co.ke"
  company_logo = "jica"
  location = "ケニア共和国ナロック"
  date_start = "2014-04-01"
  date_end = "2016-09-30"
  description = """
JICA青年海外協力隊のGISスペシャリストとして派遣され、以下の活動を行いました。

- ナロックとオロルルンガの配水管網全体（総延長約300km）をマッピング（Trimble GPS, ArcPad, QGIS）
- GISデータベースとWebGISを設計・開発（PostGIS, MapServer, Leaflet）。料金システムと連携し、料金徴収の改善に貢献
- 無収水（NRW）の分析・削減のためのDMA（District Metered Area：配水ブロック）を作成
- ケニア人の同僚への技術移転のための研修を実施。構築したGISは現在も継続して活用されている
- ケニア国内の7つの水道事業体（Nyeri Water, Kabarnet Water, Kapsabet Water, Nakuru Water, Nakuru Rural Water, Naivasha Water, Mavoko Water）に対しGIS業務のコンサルティングを実施

**スキル:** 水インフラのデータ収集, WebGIS, PostgreSQL/PostGIS, EPANET
"""

[[experience]]
  title = "ソフトウェアエンジニア"
  company = "株式会社富士通ソーシアルサイエンスラボラトリ"
  company_url = "https://www.fujitsu.com/jp/group/ssl"
  company_logo = "fujitsu"
  location = "川崎, 日本"
  date_start = "2009-04-01"
  date_end = "2017-03-31"
  description = """
GISを中心とした以下のシステムの設計・開発を行いました。2014年4月から2016年9月まではケニアでの活動のため休職し、その後復職しました。

- 自動運転車向け高精度（HD）地図の開発（ArcGIS Server, Python, Django REST framework）
- シンガポールにおける船舶の動きをマッピング・シミュレーションするシステム（Leaflet）
- 法務省の不動産登記システム向けWebGISシステム（MapServer, OpenLayers, Oracle）
- ヘルスケア管理のためのAndroidアプリケーション（Java）
- MapInfoを用いたエリアマーケティングシステム
- ダイクストラ法による経路探索を用いた物流・配送管理システム（VB.NET, SQL Server, MS Access）

**スキル:** VB.NET, Java, OpenLayers, Leaflet, MapServer, ArcGIS Server, SQL Server, MS Access, Oracle
"""

+++
