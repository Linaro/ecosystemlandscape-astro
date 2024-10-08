---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: bigdata

meta:
  keywords: "Livy"

project:
  title: "Livy"
  type: "Scala"
  logo: "/assets/projectLogos/livy.png"
  url: "Livy"
  project_official_url: "https://livy.apache.org/"
  overview: "Apache Livy is an open source REST interface for interacting with Apache Spark from anywhere. It supports executing snippets of code or programs in a Spark context that runs locally or in Apache Hadoop YARN."

supported_releases:
  - release:
    version: "v0.8.0-incubating-rc2"
    url: "https://github.com/apache/incubator-livy/releases/tag/v0.8.0-incubating-rc2"
  - release:
    version: "v0.8.0-incubating"
    url: "https://github.com/apache/incubator-livy/releases/tag/v0.8.0-incubating"
  - release:
    version: "v0.7.0-incubating-rc4"
    url: "https://github.com/apache/incubator-livy/releases/tag/v0.7.0-incubating-rc4"

project_ci:
  - CI:
    title: "Livy Upstream CI"
    status: "/assets/CI_status.png"
    url: "https://app.travis-ci.com/github/apache/incubator-livy"
---

<p>Livy</p>
