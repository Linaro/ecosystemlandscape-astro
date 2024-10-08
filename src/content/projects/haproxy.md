---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: web

meta:
  keywords: "HAProxy"

project:
  title: "HAProxy"
  type: "C"
  ci_url: "https://travis-ci.com/github/haproxy/haproxy/pull_requests"
  url: "HAProxy"
  project_official_url: "http://www.haproxy.org/"
  logo: "/assets/projectLogos/haproxy.png"
  overview: "HAProxy is a free, very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications. It is particularly suited for very high traffic web sites and powers a significant portion of the world's most visited ones. Over the years it has become the de-facto standard opensource load balancer, is now shipped with most mainstream Linux distributions, and is often deployed by default in cloud platforms."

supported_releases:
  - release:
    version: "2.6.0"
    url: "http://www.haproxy.org/#down"

project_ci:
  - CI:
    title: "HAProxy Upstream CI"
    status: "/assets/CI_status.png"
    url: "https://travis-ci.com/github/haproxy/haproxy/pull_requests"
---

<p>HAProxy</p>
