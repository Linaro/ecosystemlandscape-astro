---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: web

meta:
  keywords: "Squid, Cache"

project:
  title: "Squid-Cache"
  type: "C++"
  ci_url: "http://build.squid-cache.org/computer/arm64-rpi/"
  url: "Squid"
  project_official_url: "http://www.squid-cache.org/"
  logo: "/assets/projectLogos/squid.png"
  overview: "Squid is a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. Squid has extensive access controls and makes a great server accelerator. It runs on most available operating systems, including Windows and is licensed under the GNU GPL."

supported_releases:
  - release:
    version: "5.6"
    url: "http://www.squid-cache.org/Versions/"

project_ci:
  - CI:
    title: "Squid-Cache Upstream CI"
    status: "/assets/CI_status.png"
    url: "http://build.squid-cache.org"
---

<p>Squid-Cache</p>
