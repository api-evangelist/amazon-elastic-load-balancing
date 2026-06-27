---
title: "Amazon EKS now supports customer-routed control plane egress"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/amazon-eks-customer-routed-control-plane-egress"
date: "2026-06-18"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon EKS now lets you route outbound Kubernetes API server traffic, including admission webhook callbacks, OIDC provider lookups, and aggregate API server requests, through your own Amazon VPC where you control routing, security groups, and egress path. Set controlPlaneEgressMode to CUSTOMER_ROUTED when creating or updating a cluster, and enforce it organization-wide with the eks:controlPlaneEgressMode IAM condition key. Available at no additional cost in all Regions where EKS is offered.
