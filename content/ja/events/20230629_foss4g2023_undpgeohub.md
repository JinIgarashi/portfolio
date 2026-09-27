---

title: "[FOSS4G2023] UNDP's one stop shop for cloud based geospatial data visualisation and analytical tool
"
subtitle: ""
summary: "Presented a talk about UNDP GeoHub"
authors: ["me"]
tags: ["FOSS4G"]
categories: []
date: 2023-06-29T11:30:00
lastmod: 2023-06-29T11:30:00
featured: false
draft: false

projects: []
---

United Nations Development Programme (UNDP) is a United Nations agency tasked with helping countries eliminate poverty and achieve sustainable economic growth and human development.

Recent advances in technology and information management have resulted in large quantities of data being available to support improved data driven decision making across the organization. In this context, UNDP has developed a corporate data strategy to accelerate its transformation into a data-driven organisation. Geo-spatial data is included in this strategy and plays an important role in the organization. However, the large scale adoption and integration of geo-spatial data was obstructed in the past by issues related to data accessibility (silos located in various country offices), interoperability as well as sub-optimal hard and soft infrastructure or know-how.
All this issues have been addressed recently, when UNDP SGD integration started developing a geospatial hub - GeoHub - to provide geospatial data visualisation and analytical tools to UNDP staff and policymakers.

UNDP GeoHub is a repository of a wide array of data sets of the most recent time span available at your fingertips! It is a centralized ecosystem of geospatial data and services to support development policymakers. It allows users to search and visualise datasets, compute dynamic statistics and download the data. In addition, GeoHub provides a feature to share their maps with the community easily. With our repository, you can also upload to share your valuable data to share with the community! It connects geospatial knowledge and know-how across the organization to enhance evidence-based decision-making with relevant data-led insights.

Geohub ecosystem consists of sveltekit & maplibre based frontend web applications and various FOSS4G software in the backend side. PostgreSQL/PostGIS, titiler, pg_tileserv and martin are deployed in Azure Kubernetes (AKS) to provide advanced visualisation and analysis for users. All source code is published in Github with an open-source license.

the abstract is available [this page](https://talks.osgeo.org/foss4g-2023/talk/8TFHPG/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/JCgNnMAtCI4?si=382QBrFSW12EFZ6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>