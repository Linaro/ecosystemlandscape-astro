---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: cloud

meta:
  keywords: "Istio"

project:
  title: "Istio"
  type: "Go"
  ci_url: "https://prow.istio.io/"
  url: "Istio"
  project_official_url: "https://istio.io/"
  logo: "/assets/projectLogos/istio.png"
  overview: "Istio extends Kubernetes to establish a programmable, application-aware network using the powerful Envoy service proxy. Working with both Kubernetes and traditional workloads, Istio brings standard, universal traffic management, telemetry, and security to complex deployments."

supported_releases:
  - release:
    version: "1.0.2"
    url: "https://github.com/istio/proxy/releases/tag/1.0.2"

project_ci:
  - CI:
    title: "Istio Upstream CI"
    status: "/assets/CI_status.png"
    url: "https://prow.istio.io/"
---

<p>Istio</p>
