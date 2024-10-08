---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: libraries

meta:
  keywords: "Git"

project:
  title: "Git"
  type: "C"
  ci_url: "https://github.com/git/git/actions"
  url: "https://github.com/git/git"
  project_official_url: "https://git-scm.com/"
  logo: "/assets/projectLogos/git.png"
  overview: "Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows."

supported_releases:
  - release:
    version: "v2.42.0"
    url: "https://github.com/git/git/archive/refs/tags/v2.42.0.tar.gz"
  - release:
    version: "v2.42.0-rc2"
    url: "https://github.com/git/git/archive/refs/tags/v2.42.0-rc2.tar.gz"
  - release:
    version: "v2.42.0-rc1"
    url: "https://github.com/git/git/archive/refs/tags/v2.42.0-rc1.tar.gz"

work_items:
  - work:
    title: "merge: --ff-one-only to apply FF if commit is one"
    url: "https://github.com/git/git/pull/1599"
    status: "Open"
  - work:
    title: "typo: fix the typo 'neeed' into 'needed' in the comment under merge-o…"
    url: "https://github.com/git/git/pull/1592"
    status: "Open"
  - work:
    title: "[Outreachy][PATCH v2] branch.c: adjust error messages to coding guidelines"
    url: "https://github.com/git/git/pull/1590"
    status: "Open"

events:
  - event:
    title: "LINUX FU: DEEP GIT REBASING"
    type: "Blog"
    url: "https://hackaday.com/2023/10/17/linux-fu-deep-git-rebasing/"
    language: "English"
  - event:
    title: "Measuring Git performance with OpenTelemetry"
    type: "Blog"
    url: "https://github.blog/2023-10-16-measuring-git-performance-with-opentelemetry/"
    language: "English"
---

<p>Git</p>
