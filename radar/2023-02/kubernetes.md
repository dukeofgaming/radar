---
title: Kubernetes
ring: adopt
quadrant: platforms-and-aoe-services
tags:
  - kubernetes
  - gcp
  - migration
  - cloudrun
---

Led a strategic migration from CloudRun to Google Kubernetes Engine (GKE) for a mainframe modernization project at Flexion Inc. This initiative involved evaluating the benefits of Kubernetes-native patterns, creating Terraform modules for deployment, and adapting existing CI/CD pipelines to support a more scalable and flexible infrastructure.

Worked on getting GKE deployed and configured through Terraform and Github Actions through a Helm chart generic to all microservices in the project, using the Gateway API and HTTPRoute resources to integrate GCP PubSub endpoints and a BackendPolicy to configure TLS for internal endpoints using Kubernetes' CoreDNS.