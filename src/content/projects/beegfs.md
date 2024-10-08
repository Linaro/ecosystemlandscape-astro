---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: storage

meta:
  keywords: "BeeGFS"

project:
  title: "BeeGFS"
  type: "C"
  ci_url: "https://www.beegfs.io/"
  url: "BeeGFS"
  project_official_url: "https://www.beegfs.io/"
  logo: "/assets/projectLogos/beegfs.png"
  overview: "BeeGFS is a hardware-independent POSIX parallel file system (a.k.a Software-defined Parallel Storage) developed with a strong focus on performance and designed for ease of use, simple installation, and management."

supported_releases:
  - release:
    version: "v7.0+"
    url: "https://git.beegfs.io/pub/v7"

work_items:
  - work:
    title: "BeeGFS Performance Test on Arm64"
    url: "https://linaro.atlassian.net/browse/STOR-98"
    status: "WIP"
  - work:
    title: "Fix BeeGFS copy_to_user issue"
    url: "https://linaro.atlassian.net/browse/STOR-27"
    status: "DONE"

events:
  - event:
    title: "BeeGFS claim Arm support"
    type: "Release Notes"
    url: "https://doc.beegfs.io/7.3.0/release_notes.html"
    language: "English"
  - event:
    title: "ThinkParQ Announces New Collaboration with Huawei to Deliver Arm Compatibility and Support"
    type: "Announcement"
    url: "https://www.hpcwire.com/off-the-wire/thinkparq-announces-new-collaboration-with-huawei/"
    language: "English"
  - event:
    title: "Linaro Connect LVC21F-203 The Progress for Distributed Storage on Arm64"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc21f/lvc21f-203/"
    language: "English"

---

<p>BeeGFS</p>
