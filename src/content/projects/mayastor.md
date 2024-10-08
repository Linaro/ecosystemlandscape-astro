---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: storage

meta:
  keywords: "Mayastor"

project:
  title: "Mayastor"
  type: "Rust"
  ci_url: "https://github.com/openebs/mayastor/actions"
  url: "Mayastor"
  project_official_url: "https://mayastor.gitbook.io/"
  logo: "/assets/projectLogos/mayastor.svg"
  overview: "Mayastor is currently under development as a sub project of the Open Source CNCF project OpenEBS. OpenEBS is a Container Attached Storage or CAS solution which extends Kubernetes with a declarative data plane, providing flexible persistent storage for stateful applications."

supported_releases:
  - release:
    version: "develop branch"
    url: "https://github.com/openebs/mayastor/tree/develop"

work_items:
  - work:
    title: "Mayastor Performance Benchmark on Arm64"
    url: "https://linaro.atlassian.net/browse/STOR-37"
    status: "WIP"
  - work:
    title: "Mayastor Build and function validation on Arm64"
    url: "https://linaro.atlassian.net/browse/STOR-35"
    status: "DONE"
  - work:
    title: "Fix arm64 build"
    url: "https://github.com/openebs/mayastor/pull/1121"
    status: "DONE"
  - work:
    title: "feat: aarch64 support"
    url: "https://github.com/openebs/mayastor/pull/671"
    status: "DONE"

---

<p>Mayastor</p>
