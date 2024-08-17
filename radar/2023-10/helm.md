---
title: Helm
ring: adopt
quadrant: platforms-and-aoe-services
tags:
  - kubernetes
  - gcp
  - cloudrun
---

Once all services were migrated from CloudRun to Kubernetes, I progressively refactored a Terraform module mirroring the design of a chart to be able to switch the service from deployment target to deocuple all CloudRun-related infrastructure.

Once that was done, deployed the Helm chart in it's own separate GitHub Action, effectively removing the state dependency of Helm deployments from Terraform, no longer needing to invoke the Terraform Helm provider, and only needing to pass some variables picked up by a values.yaml file for each different service.