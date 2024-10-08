---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: database

meta:
  keywords: "etcd"

project:
  title: "etcd"
  type: "go"
  ci_url: "https://etcd.io/"
  url: "Etcd"
  project_official_url: "https://etcd.io/"
  logo: "/assets/projectLogos/etcd.png"
  overview: "etcd is a strongly consistent, distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. It gracefully handles leader elections during network partitions and can tolerate machine failure, even in the leader node."

supported_releases:
  - release:
    version: "v3.5.1"
    url: "https://github.com/etcd-io/etcd/releases/tag/v3.5.1"

---

<p>etcd</p>
