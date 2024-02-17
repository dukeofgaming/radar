---
title: Kubernetes
ring: trial
quadrant: platforms-and-aoe-services
tags:
  - kubernetes
  - blips
---

Used Kubernetes for the first time for Flexion’s interview challenge. Being cloud deployment one of the requirements I wanted a way that would allow me to test my application locally and have a reliable way to have a portable deployment to AWS or GCP

After reading about operators and GitOps, I chose flux and setup a very simple local CICD pipeline with Jenkins and Artifactory with Docker Compose.

The result was a local dev loop that could deploy locally and remotely at the same time, upon releasing a new image and changing the Kubernetes deployment’s image reference.