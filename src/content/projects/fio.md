---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: libraries

meta:
  keywords: "Fio"

project:
  title: "Fio"
  type: "C"
  url: "https://fio.readthedocs.io/en/latest/fio_doc.html"
  project_official_url: "https://github.com/axboe/fio"
  logo: "/assets/projectLogos/fio.png"
  overview: "Fio spawns a number of threads or processes doing a particular type of I/O action as specified by the user. fio takes a number of global parameters, each inherited by the thread unless otherwise parameters given to them overriding that setting is given. The typical use of fio is to write a job file matching the I/O load one wants to simulate."

supported_releases:
  - release:
    version: "fio-3.36"
    url: "https://github.com/axboe/fio/archive/refs/tags/fio-3.36.tar.gz"
  - release:
    version: "fio-3.35"
    url: "https://github.com/axboe/fio/archive/refs/tags/fio-3.35.tar.gz"
  - release:
    version: "fio-3.34"
    url: "https://github.com/axboe/fio/archive/refs/tags/fio-3.34.tar.gz"
---

<p>Fio</p>
