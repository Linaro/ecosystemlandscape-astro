---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: web

meta:
  keywords: "Node.js"

project:
  title: "Node.js"
  type: "JavaScript, C, C++"
  ci_url: "https://nodejs.org"
  url: "https://nodejs.org"
  project_official_url: "https://nodejs.org/"
  logo: "/assets/projectLogos/node.png"
  overview: "Node.js is an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside a browser. JavaScript performance is great on Arm in both Android and server platforms."

supported_releases:

  - release:
    version: "3.3.1"
    url: "https://iojs.org/download/release/v3.3.1/"
  - release:
    version: "Latest"
    url: "https://nodejs.org/en/download/current/"

work_items:
  - work:
    title: "build: add basic arm64 support"
    url: "https://github.com/nodejs/node/pull/1028"
    status: "DONE"
  - work:
    title: "build: Re-enable openssl asm for arm64"
    url: "https://github.com/nodejs/node/pull/28180"
    status: "DONE"
  - work:
    title: "test: improve test-arm-math-illegal-instruction.js"
    url: "https://github.com/nodejs/node/pull/37670"
    status: "DONE"
---

<p>Node.js</p>
