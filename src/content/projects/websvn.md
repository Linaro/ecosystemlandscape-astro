---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: middleware

meta:
  keywords: "WebSVN"

project:
  title: "WebSVN"
  type: "PHP"
  url: "WebSVN"
  project_official_url: "https://websvnphp.github.io/"
  logo: "/assets/projectLogos/websvn.jpeg"
  overview: "WebSVN offers a view onto your subversion repositories that's been designed to reflect the Subversion methodology. You can view the log of any file or directory and see a list of all the files changed, added or deleted in any given revision. You can also view the differences between two versions of a file so as to see exactly what was changed in a particular revision."

supported_releases:
  - release:
    version: "2.8.2"
    url: "https://github.com/websvnphp/websvn/releases/tag/2.8.2"
  - release:
    version: "2.8.1"
    url: "https://github.com/websvnphp/websvn/releases/tag/2.8.1"
  - release:
    version: "2.7.0"
    url: "https://github.com/websvnphp/websvn/releases/tag/2.7.0"

work_items:
  - work:
    title: "Character encoding mistakes arising from change in mb_detect_encoding"
    url: "https://github.com/websvnphp/websvn/issues/195"
    status: "TODO"
  - work:
    title: "Various smaller errors captured in php_error.log"
    url: "https://github.com/websvnphp/websvn/issues/193"
    status: "TODO"
  - work:
    title: "Syntax error in revision argument when accessing deleted file"
    url: "https://github.com/websvnphp/websvn/issues/191"
    status: "TODO"

---

<p>WebSVN</p>
