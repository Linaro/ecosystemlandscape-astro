---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: libraries

meta:
  keywords: "kcat (kafkacat)"

project:
  title: "kcat (kafkacat)"
  type: "C"
  url: "https://github.com/edenhill/kcat"
  project_official_url: "https://github.com/edenhill/kcat"
  logo: "/assets/projectLogos/kcat.png"
  overview: "kcat is a generic non-JVM producer and consumer for Apache Kafka >=0.8, think of it as a netcat for Kafka.In producer mode kcat reads messages from stdin, delimited with a configurable delimiter (-D, defaults to newline), and produces them to the provided Kafka cluster (-b), topic (-t) and partition (-p).In consumer mode kcat reads messages from a topic and partition and prints them to stdout using the configured message delimiter."

supported_releases:
  - release:
    version: "kcat 1.7.0"
    url: "https://github.com/edenhill/kcat/archive/refs/tags/1.7.0.tar.gz"
  - release:
    version: "kcat 1.6.0"
    url: "https://github.com/edenhill/kcat/archive/refs/tags/1.6.0.tar.gz"
  - release:
    version: "kcat 1.5.0"
    url: "https://github.com/edenhill/kcat/archive/refs/tags/1.5.0.tar.gz"
---

<p>kcat (kafkacat)</p>
