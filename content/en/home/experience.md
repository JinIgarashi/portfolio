+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 23  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Software Engineer"
  company = "Fracta"
  company_url = "https://fracta.ai"
  company_logo = "fracta"
  location = "Remote (work from Japan)"
  date_start = "2025-09-01"
  date_end = ""
  description = """
Fracta is a software company using artificial intelligence to assess the risk of water and sewer pipeline failures and to support pipeline maintenance planning for utilities worldwide, mainly in the USA and Japan.

- Work in the engineering team as a full-stack software engineer.
- Develop new features, fix bugs and maintain the system from the web frontend to the backend and database.
- Work on map-based user interfaces for water and sewer utilities.

**Skills:** Mapbox, Node.js (JavaScript), Python, Vue.js, Django, PostgreSQL/PostGIS, AWS
"""

[[experience]]
  title = "Full Stack GIS Developer"
  company = "United Nations Development Programme (UNDP)"
  company_url = "https://www.undp.org"
  company_logo = "undp"
  location = "New York (Work remotely from UK/Japan)"
  date_start = "2021-12-01"
  date_end = "2025-08-31"
  description = """
Developed the [UNDP GeoHub](https://geohub.data.undp.org) platform, a part of the Data Futures Exchange (DFx), in the SDG Integration Team, Bureau for Policy and Programme Support. Worked remotely from the United Kingdom (until October 2024) and Japan (from November 2024).

- Developed GeoHub, new open-source software that provides advanced data visualization, analysis and sharing tools to UNDP staff and policymakers without geospatial skills.
- Built the SvelteKit & MapLibre frontend and the FOSS4G backend (PostgreSQL/PostGIS, titiler, pg_tileserv) running on Azure Kubernetes Service.
- Implemented a data upload pipeline, dataset/map permission management, social login, raster analytics (titiler algorithms), STAC integration and a static map image API.
- Developed [RAPIDA](https://github.com/UNDP-Data/rapida), a semi-automated geospatial assessment tool for rapid crisis response (November 2024 – August 2025).
- Published all source code on GitHub under open-source licenses and presented the work at FOSS4G 2023 and FOSS4G Europe 2024.

Contract history:

- Individual contractor – GIS Consultant (part time), December 2021 – September 2022
- IPSA-9 Short term – GIS Developer (full time), September 2022 – July 2023
- IPSA-9 – Full Stack GIS Developer (full time), August 2023 – August 2025

**Skills:** MapLibre, Mapbox, Node.js (JavaScript), Python, Svelte/SvelteKit, PostgreSQL/PostGIS, titiler, pg_tileserv, STAC, Azure (App Service, Blob Storage, PubSub, Kubernetes, etc.)
"""

[[experience]]
  title = "Software Engineer"
  company = "Geolonia Inc."
  company_url = "https://geolonia.com"
  company_logo = "geolonia"
  location = "Japan (Remote)"
  date_start = "2021-08-01"
  date_end = "2022-03-31"
  description = """
Worked part-time and remotely with Geolonia to develop open-source GIS applications.

- Developed open-source software for open reverse geocoding.
- Contributed to [unit/charites](https://github.com/unvt/charites), a CLI tool for writing and managing MapLibre map styles.

**Skills:** MapLibre, geocoding, reverse geocoding, map styling
"""

[[experience]]
  title = "Software Engineer"
  company = "Ocean Eyes Co., Ltd."
  company_url = "https://oceaneyes.co.jp/en"
  location = "Japan (Remote)"
  date_start = "2021-06-01"
  date_end = "2021-11-30"
  description = """
Enhanced the existing WebGIS system and developed new features as a freelancer.

- Migrated the web map from Leaflet to Mapbox GL JS on Vue.js.
- Developed various new features on the website.
- Established CI/CD to manage the source code repository easily and sustainably.

**Skills:** Node.js (JavaScript), Mapbox, Leaflet, Vue.js
"""

[[experience]]
  title = "Software Engineer"
  company = "MIERUNE Inc."
  company_url = "https://mierune.co.jp"
  company_logo = "mierune"
  location = "Hokkaido, Japan"
  date_start = "2020-10-01"
  date_end = "2021-08-15"
  description = """
Developed WebGIS systems using FOSS4G (Free & Open Source Software for Geospatial) as a GIS specialist.

- Developed WebGIS applications for clients with open-source geospatial software.
- Built geocoding services with Photon (open-source geocoder) and Elasticsearch.
- Developed backend systems with Django and deployed them to the cloud.
- Joined several open-source GIS community activities.

**Skills:** AWS, Google Cloud, Kubernetes, geocoding, Elasticsearch, Django, Python
"""

[[experience]]
  title = "Software Engineer"
  company = "ONE COMPATH CO., LTD."
  company_url = "https://onecompath.com"
  location = "Tokyo, Japan"
  date_start = "2020-01-17"
  date_end = "2020-09-30"
  description = """
Developed and operated "MAPION", one of the most popular web map services in Japan.

- Developed and improved the operation of the map delivery system using Mapbox Vector Tiles and MapServer on Amazon Web Services (AWS).
- Maintained map data in PostgreSQL/PostGIS.

**Skills:** AWS, Mapbox, MapServer, PostgreSQL/PostGIS
"""

[[experience]]
  title = "Consultant"
  company = "KOKUSAI KOGYO CO., LTD."
  company_url = "https://www.kkc.co.jp/english/index.html"
  company_logo = "kkc"
  location = "Tokyo, Japan"
  date_start = "2017-04-01"
  date_end = "2019-12-31"
  description = """
Conducted the following projects funded by the Japan International Cooperation Agency (JICA).

- [The Project for Strengthening Operation and Maintenance of Rural Water Supply Systems in Rwanda (RWASOM)](project/201806-rwasom/) (06/2018 – 12/2019)
- [Survey for the Establishment of the Experimental Field for the GNSS System Development in the Kingdom of Thailand](project/201811-thai_cors/) (11/2018 – 11/2019)
- [Preparatory Survey for the Project for Strengthening Nzove-Ntora Principal Water Transmission Pipeline in Kigali City, Rwanda](project/201710-nzove-ntora/) (10/2017 – 11/2018)

In the RWASOM project, conducted training workshops for data collection and sharing with FOSS4G applications, then designed and created the GIS database and data sharing platform for rural water supply management. Collaborated with Rwandan colleagues to complete the mapping of all water supply systems in the country. The system uses PostGIS, Lizmap/QGIS Server, QGIS Desktop, QField and Garmin GPS.

**Skills:** geospatial data collection, EPANET, water supply, design/planning of water infrastructure, QGIS, PostGIS
"""

[[experience]]
  title = "GIS Specialist (JICA Volunteer)"
  company = "NAROK WATER AND SEWERAGE SERVICES CO., LTD."
  company_url = "https://www.narwassco.co.ke"
  company_logo = "jica"
  location = "Narok, Kenya"
  date_start = "2014-04-01"
  date_end = "2016-09-30"
  description = """
Worked as a GIS specialist funded by JICA and conducted the following activities.

- Mapped the entire water distribution network (approximately 300 km of pipelines in total) in Narok and Ololulung'a towns (Trimble GPS, ArcPad, QGIS).
- Designed and developed a GIS database and WebGIS (PostGIS, MapServer, Leaflet). The system is linked to the billing system and helps improve revenue collection.
- Created DMAs (District Metered Areas) for analyzing and improving Non-Revenue Water management.
- Conducted training to transfer technical knowledge to Kenyan colleagues; the GIS system has been continuously used since it was developed.
- Consulted on GIS work for 7 water service providers in Kenya (Nyeri Water, Kabarnet Water, Kapsabet Water, Nakuru Water, Nakuru Rural Water, Naivasha Water and Mavoko Water).

**Skills:** data collection for water infrastructure, WebGIS, PostgreSQL/PostGIS, EPANET
"""

[[experience]]
  title = "Software Engineer"
  company = "FUJITSU SOCIAL SCIENCE LABORATORY, LTD."
  company_url = "https://www.fujitsu.com/jp/group/ssl/en/"
  company_logo = "fujitsu"
  location = "Kanagawa, Japan"
  date_start = "2009-04-01"
  date_end = "2017-03-31"
  description = """
Designed and developed the following systems, most of them related to GIS. Took a leave of absence while working in Kenya between April 2014 and September 2016, then returned to the company.

- HD map development for autonomous vehicles (ArcGIS Server, Python, Django REST framework)
- A system for mapping and simulating the movement of ships in Singapore (Leaflet)
- A WebGIS system for the Real Property Registration system of the Ministry of Justice of Japan (MapServer, OpenLayers, Oracle)
- An Android application for health care management (Java)
- An area marketing system using MapInfo
- A logistics and distribution management system with Dijkstra's routing algorithm (VB.NET, SQL Server, MS Access)

**Skills:** VB.NET, Java, OpenLayers, Leaflet, MapServer, ArcGIS Server, SQL Server, MS Access, Oracle
"""

+++
