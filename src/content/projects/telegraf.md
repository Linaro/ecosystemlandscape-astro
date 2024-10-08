---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: middleware

meta:
  keywords: "Telegraf"

project:
  title: "Telegraf"
  type: "Rust"
  ci_url: "https://github.com/influxdata/telegraf/actions"
  url: "Telegraf"
  project_official_url: "https://www.influxdata.com/time-series-platform/telegraf/"
  logo: "/assets/projectLogos/telegraf.png"
  overview: "Telegraf is an agent for collecting, processing, aggregating, and writing metrics. Based on a plugin system to enable developers in the community to easily add support for additional metric collection. There are four distinct types of plugins: 1) Input Plugins collect metrics from the system, services, or 3rd party APIs. 2) Processor Plugins transform, decorate, and/or filter metrics. 3) Aggregator Plugins create aggregate metrics (e.g. mean, min, max, quantiles, etc.) 4) Output Plugins write metrics to various destinations. New plugins are designed to be easy to contribute, pull requests are welcomed, and we work to incorporate as many pull requests as possible. Consider looking at the list of external plugins as well."

supported_releases:
  - release:
    version: "1.28.3"
    url: "https://github.com/influxdata/telegraf/releases/tag/v1.28.3"
  - release:
    version: "1.28.2"
    url: "https://github.com/influxdata/telegraf/releases/tag/v1.28.2"
  - release:
    version: "1.28.1"
    url: "https://github.com/influxdata/telegraf/releases/tag/v1.28.1"

work_items:
  - work:
    title: "chore(linters): Enable perfsprint linter and fix all findings."
    url: "https://github.com/influxdata/telegraf/pull/14208"
    status: "Open"
  - work:
    title: "feat: Support proxy env vars from elastic stack plugins"
    url: "https://github.com/influxdata/telegraf/pull/14207"
    status: "Open"
  - work:
    title: "chore(linters): Fix findings found by testifylint: len"
    url: "https://github.com/influxdata/telegraf/pull/14203"
    status: "Open"

events:
  - event:
    title: "What is the Time Library in Python? A Helpful Guide"
    type: "Online Session"
    url: "https://www.influxdata.com/blog/what-is-time-library-in-python-helpful-guide"
    language: "English"
  - event:
    title: "Webinar Recap: Build an Edge-to-Cloud Architecture Using MQTT and InfluxDB"
    type: "Online Session"
    url: "https://www.influxdata.com/blog/webinar-recap-build-an-edge-to-cloud-architecture-using-mqtt-and-influxdb"
    language: "English"
---

<p>Telegraf</p>
