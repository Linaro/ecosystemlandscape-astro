---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: storage

meta:
  keywords: "Rook"

project:
  title: "Rook"
  type: "Go"
  ci_url: "https://github.com/rook/rook/actions/workflows/daily-nightly-jobs.yml"
  url: "Rook"
  project_official_url: "https://rook.github.io"
  logo: "/assets/projectLogos/rook.svg"
  overview: "Rook is an open source cloud-native storage orchestrator for Kubernetes, providing the platform, framework, and support for a diverse set of storage solutions(Ceph, Cassandra and NFS) to natively integrate with cloud-native environments. Rook turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management."

supported_releases:
  - release:
    version: "v1.4.0+"
    url: "https://github.com/rook/rook/releases/tag/v1.4.0"

project_ci:
  - CI:
    title: "Rook Github Actions CI - canary-arm64"
    status: "/assets/CI_status.png"
    url: "https://github.com/rook/rook/actions/workflows/daily-nightly-jobs.yml"

work_items:
  - work:
    title: "Add Arm64 canary integration CI job for Rook Ceph storage provider"
    url: "https://linaro.atlassian.net/browse/STOR-18"
    status: "DONE"
  - work:
    title: "Add arm64 self-hosted CI runner for Rook project"
    url: "https://linaro.atlassian.net/browse/STOR-19"
    status: "DONE"
  - work:
    title: "Fix arm64 image builds"
    url: "https://github.com/rook/rook/pull/1887"
    status: "DONE"

events:
  - event:
    title: "Linaro Connect LVC21F-203 The Progress for Distributed Storage on Arm64"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc21f/lvc21f-203/"
    language: "English"
  - event:
    title: "Cloud Native Computing Foundation Announces Rook Graduation"
    type: "Blog"
    url: "https://www.cncf.io/announcements/2020/10/07/cloud-native-computing-foundation-announces-rook-graduation/"
    language: "English"
  - event:
    title: "Ceph-CSI v2.0.0 released with multi arch image support for Arm64 images"
    type: "Blog"
    url: "https://www.humblec.com/ceph-csi-v2-0-0-released/"
    language: "English"
---

<p>Rook</p>
