---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: libraries

meta:
  keywords: "Php"

project:
  title: "Php"
  type: "Php"
  ci_url: "https://www.php.net/"
  url: "https://www.php.net/"
  logo: "/assets/projectLogos/php.png"
  project_official_url: "https://www.php.net/"
  overview: "PHP is a popular general-purpose scripting language that is especially suited to web development.
  Fast, flexible and pragmatic, PHP powers everything from your blog to the most popular websites in the world."

supported_releases:
  - release:
    version: "7.1.33"
    url: "https://github.com/php/php-src/tags?after=php-7.2.25RC1"
  - release:
    version: "Latest"
    url: "https://www.php.net/downloads"

work_items:
  - work:
    title: "Properly detect CRC32 APIs on aarch64 from configure"
    url: "https://github.com/php/php-src/pull/5564"
    status: "DONE"
  - work:
    title: "Fix range.phpt failed under RELEASE mode on ARM64 machine"
    url: "https://github.com/php/php-src/pull/7527"
    status: "DONE"
---

<p>php</p>
