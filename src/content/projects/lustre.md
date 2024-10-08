---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: storage

meta:
  keywords: "Lustre"

project:
  title: "Lustre"
  type: "C"
  ci_url: "https://testing.whamcloud.com/test_sessions"
  url: "Lustre"
  project_official_url: "https://www.lustre.org"
  logo: "/assets/projectLogos/lustre.png"
  overview: "The Lustre® file system is an open-source, parallel file system that supports many requirements of leadership class HPC simulation environments. The Lustre file system provides a POSIX compliant file system interface, can scale to thousands of clients, petabytes of storage and hundreds of gigabytes per second of I/O bandwidth."

supported_releases:
  - release:
    version: "v2.14.0+"
    url: "https://wiki.lustre.org/Lustre_2.14.0_Changelog"

project_ci:
  - CI:
    title: "Lustre CentOS8 Client CI - review-ldiskfs-arm"
    status: "/assets/CI_status.png"
    url: "https://testing.whamcloud.com/test_sessions"

work_items:
  - work:
    title: "Lustre Server End Non-critical Bug Fix"
    url: "https://linaro.atlassian.net/browse/STOR-70"
    status: "TODO"
  - work:
    title: "Lustre Server End Critical Bug Fix"
    url: "https://linaro.atlassian.net/browse/STOR-69"
    status: "WIP"
  - work:
    title: "Lustre old client bugs fix"
    url: "https://linaro.atlassian.net/browse/STOR-8"
    status: "WIP"
  - work:
    title: "add support for arm64"
    url: "https://jira.whamcloud.com/browse/LU-6766"
    status: "DONE"

events:
  - event:
    title: "Linaro Connect LVC21F-203 The Progress for Distributed Storage on Arm64"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc21f/lvc21f-203/"
    language: "English"
  - event:
    title: "Flash Based Lustre Filesystem for the Arm‐based Supercomputer‐Astra"
    type: "Online Session"
    url: "https://vimeo.com/339634630"
    language: "English"
  - event:
    title: "Status of Lustre on ARM platforms"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/san19/san19-224/"
    language: "English"
  - event:
    title: "Arm + Lustre in HPC"
    type: "Online Session"
    url: "https://insidehpc.com/2018/12/video-arm-lustre-hpc/"
    language: "English"
  - event:
    title: "Lustre File System on ARM"
    type: "Online Session"
    url: "https://insidehpc.com/2018/02/video-lustre-file-system-arm/"
    language: "English"
---

<p>Lustre</p>
