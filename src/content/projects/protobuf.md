---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: middleware

meta:
  keywords: "Protobuf"

project:
  title: "Protobuf"
  type: "C++"
  ci_url: "https://developers.google.com/protocol-buffers/"
  url: "Protobuf"
  project_official_url: "https://developers.google.com/protocol-buffers/"
  logo: "/assets/projectLogos/protobuf.png"
  overview: "Protocol buffers are Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data – think XML, but smaller, faster, and simpler."

supported_releases:
  - release:
    version: "v3.5.0"
    url: "https://github.com/protocolbuffers/protobuf/releases/tag/v3.5.0"
  - release:
    version: "Latest"
    url: "https://developers.google.com/protocol-buffers/docs/downloads"

work_items:
  - work:
    title: "Add support to build aarch64 wheels and artifacts "
    url: "https://github.com/protocolbuffers/protobuf/pull/8196"
    status: "DONE"
  - work:
    title: "Enable crosscompiling aarch64 python wheels under dockcross manylinux docker image "
    url: "https://github.com/protocolbuffers/protobuf/pull/8280"
    status: "DONE"
  - work:
    title: "Emulated python aarch64 tests "
    url: "https://github.com/protocolbuffers/protobuf/pull/8392"
    status: "DONE"
---

<p>Protobuf</p>
