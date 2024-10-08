---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: storage

meta:
  keywords: "SPDK"

project:
  title: "SPDK"
  type: "C"
  ci_url: "https://spdk.io/"
  url: "https://spdk.io/"
  logo: "/assets/projectLogos/spdk.png"
  overview: "The Storage Performance Development Kit (SPDK) provides a set of tools and libraries for writing high performance, scalable, user-mode storage applications. It achieves high performance by moving all of the necessary drivers into userspace and operating in a polled mode instead of relying on interrupts, which avoids kernel context switches and eliminates interrupt handling overhead."

supported_releases:
  - release:
    version: "v21.10"
    url: "https://github.com/spdk/spdk/tree/v21.10"
  - release:
    version: "v21.04"
    url: "https://github.com/spdk/spdk/tree/v21.04"
  - release:
    version: "v20.10"
    url: "https://github.com/spdk/spdk/tree/v20.10"
  - release:
    version: "v20.04"
    url: "https://github.com/spdk/spdk/tree/v20.04"

project_ci:
  - CI:
    title: "SPDK Mellanox CI on Aarch64"
    status: "/assets/CI_status.png"
    url: "https://swx-ci.mellanox.com/spdk-test/blue/organizations/jenkins/basic_test_spdk_upstream_ci/activity"

events:
  - event:
    title: "LVC20-111 Boost storage performance using SPDK on Arm"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc20/lvc20-111/"
    language: "English"
  - event:
    title: "LVC21-208: Embracing High Performance Flash Storage with Arm"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc21/lvc21-208/"
    language: "English"
  - event:
    title: "BKK19-104 - Latest storage status on Arm"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/bkk19/bkk19-104/"
    language: "English"
---

<p>SPDK</p>
