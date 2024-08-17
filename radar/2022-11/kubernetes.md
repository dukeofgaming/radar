---
title: Kubernetes
ring: adopt
quadrant: platforms-and-aoe-services
tags:
  - kubernetes
  - cloudrun
---

Worked on getting GKE deployed and configured through Terraform and Github Actions through a Helm chart generic to all microservices in the project, using the Gateway API and HTTPRoute resources to integrate GCP PubSub endpoints and a BackendPolicy to configure TLS for internal endpoints using Kubernetes' CoreDNS.