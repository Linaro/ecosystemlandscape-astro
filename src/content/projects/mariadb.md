---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: database

meta:
  keywords: "MariaDB"

project:
  title: "MariaDB"
  type: "C"
  ci_url: "https://buildbot.mariadb.org/#/builders"
  url: "MariaDB"
  project_official_url: "https://mariadb.org/"
  logo: "/assets/projectLogos/mariadb.jpg"
  overview: "MariaDB Server is one of the most popular open source relational databases. It’s made by the original developers of MySQL and guaranteed to stay open source. It is part of most cloud offerings and the default in most Linux distributions.

  It is built upon the values of performance, stability, and openness, and MariaDB Foundation ensures contributions will be accepted on technical merit. Recent new functionality includes advanced clustering with Galera Cluster 4, compatibility features with Oracle Database and Temporal Data Tables, allowing one to query the data as it stood at any point in the past."

supported_releases:
  - release:
    version: "10.2"
    url: "https://mariadb.org/download/#mariadb-repositories"
  - release:
    version: "10.3"
    url: "https://mariadb.org/download/#mariadb-repositories"
  - release:
    version: "10.4"
    url: "https://mariadb.org/download/#mariadb-repositories"
  - release:
    version: "10.5"
    url: "https://mariadb.org/download/#mariadb-repositories"
  - release:
    version: "10.6"
    url: "https://mariadb.org/download/#mariadb-repositories"

project_ci:
    - CI:
      title: "MariaDB Upstream AArch64 CI"
      status: "/assets/CI_status.png"
      url: "https://buildbot.mariadb.org/#/builders?tags=%2Baarch64"

events:
    - event:
      title: "ARM improvements in 2020"
      type: "Blog"
      url: "https://mariadb.org/arm-improvements-in-2020/"
      language: "English"
    - event:
      title: "MariaDB Server’s continuous integration & testing available to community"
      type: "Blog"
      url: "https://mariadb.org/buildbot-mariadb-org-2/"
      language: "English"
    - event:
      title: "MariaDB on ARM"
      type: "Online Session"
      url: "https://mariadb.org/fest2020/arm/"
      language: "English"
    - event:
      title: "Why run MariaDB on ARM?"
      type: "Blog"
      url: "https://mysqlonarm.github.io/Why-run-mariadb-on-arm/"
      language: "English"

---

<p>MariaDB</p>
