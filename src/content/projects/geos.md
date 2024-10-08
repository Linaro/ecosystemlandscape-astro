---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: middleware

meta:
  keywords: "GEOS"

project:
  title: "GEOS"
  type: "C++"
  url: "GEOS"
  project_official_url: "https://libgeos.org/"
  logo: "/assets/projectLogos/geos.png"
  overview: "GEOS is a C++ library for performing operations on two-dimensional vector geometries. It is primarily a port of the JTS Topology Suite Java library. It provides many of the algorithms used by PostGIS, the Shapely package for Python, the sf package for R, and others."

supported_releases:
  - release:
    version: "3.12.0"
    url: "https://github.com/libgeos/geos/releases/tag/3.12.0"
  - release:
    version: "3.11.2"
    url: "https://github.com/libgeos/geos/releases/tag/3.11.2"
  - release:
    version: "3.11.0"
    url: "https://github.com/libgeos/geos/releases/tag/3.11.0"

events:
  - event:
    title: "Version 3.12.0"
    type: "News"
    url: "https://libgeos.org/posts/2023-06-27-geos-3-12-released/"
    language: "English"
  - event:
    title: "Version 3.11.2"
    type: "News"
    url: "https://libgeos.org/posts/2023-03-16-geos-3-11-2-released/"
    language: "English"

project_ci:
  - CI:
    title: "GEOS Upstream CI"
    status: "/assets/CI_status.png"
    url: "https://beats-ci.elastic.co/job/Beats/"
---

<p>GEOS</p>
