---
layout: ../../layouts/ProjectLayout.astro
permalink: /:title/
category: cloud

meta:
  keywords: "Kubernetes"

project:
  title: "Kubernetes"
  type: "Go"
  ci_url: "https://prow.k8s.io/?job=*arm64*"
  url: "Kubernetes"
  project_official_url: "https://kubernetes.io/"
  logo: "/assets/projectLogos/kubernetes.png"
  overview: "Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications. It groups containers that make up an application into logical units for easy management and discovery. Kubernetes builds upon 15 years of experience of running production workloads at Google, combined with best-of-breed ideas and practices from the community."

supported_releases:
  - release:
    version: "v1.22"
    url: "https://v1-22.docs.kubernetes.io/docs/home"
  - release:
    version: "v1.23"
    url: "https://v1-23.docs.kubernetes.io/docs/home"
  - release:
    version: "v1.24"
    url: "https://v1-24.docs.kubernetes.io/docs/home"
  - release:
    version: "v1.25"
    url: "https://v1-25.docs.kubernetes.io/docs/home"
  - release:
    version: "Latest"
    url: "https://kubernetes.io/docs/home/"

project_ci:
  - CI:
    title: "Kubernetes Prow CI"
    status: "/assets/CI_status.png"
    url: "https://prow.k8s.io/?job=*arm64*"

events:
  - event:
    title: "Canonical’s Distribution of Kubernetes supported on Arm architecture"
    type: "Blog"
    url: "https://ubuntu.com/blog/canonicals-distribution-of-kubernetes-supported-on-arm-architecture"
    language: "English"
  - event:
    title: "IoT Application Running on KubeEdge Arm Platform"
    type: "Online Session"
    url: "https://www.youtube.com/watch?v=sP3RvkiGDw8"
    language: "English"
---

<p>Kubernetes</p>
