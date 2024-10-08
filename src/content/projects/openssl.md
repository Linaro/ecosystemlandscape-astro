---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: libraries

meta:
  keywords: "OpenSSL"

project:
  title: "OpenSSL"
  type: "C"
  ci_url: "https://travis-ci.com/github/openssl/openssl"
  url: "https://travis-ci.com/github/openssl/openssl"
  project_official_url: "https://www.openssl.org/"
  logo: "/assets/projectLogos/openssl.png"
  overview: "OpenSSL is a robust, commercial-grade, full-featured Open Source Toolkit for the Transport Layer Security (TLS) protocol formerly known as the Secure Sockets Layer (SSL) protocol. The protocol implementation is based on a full-strength general purpose cryptographic library, which can also be used stand-alone."
supported_releases:
  - release:
    version: "1.1.1.x"
    url: "https://www.openssl.org/source/old/1.1.1/"
  - release:
    version: "Latest"
    url: "https://www.openssl.org/source/"

work_items:
  - work:
    title: "aarch64: support BTI and pointer authentication in assembly (openssl-3.0)"
    url: "https://github.com/openssl/openssl/pull/16765"
    status: "DONE"
  - work:  
    title: "SM4 optimization for ARM by HW instruction"
    url: "https://github.com/openssl/openssl/pull/17455"
    status: "DONE"
  - work:  
    title: "Fix detection of ARMv7 and ARM64 CPU features on FreeBSD"
    url: "https://github.com/openssl/openssl/pull/17079"
    status: "DONE"

---

<p>OpenSSL</p>

---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: libraries

meta:
  keywords: "OpenSSL"

project:
  title: "OpenSSL"
  type: "C"
  ci_url: "https://travis-ci.com/github/openssl/openssl"
  url: "https://travis-ci.com/github/openssl/openssl"
  logo: "/assets/projectLogos/openssl.png"
---

<p>OpenSSL</p>
