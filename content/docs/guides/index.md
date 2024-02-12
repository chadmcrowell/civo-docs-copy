---
sidebar_position: 1
title: Civo Guides
description: Guides and best practices that allow you to quickly get up and running with Civo infrastructure 
---

<head>
  <title>Civo Guides | Civo Documentation</title>
</head>

## Guides

### Standing up a cluster

We accept all major cards supported by Stripe, including American Express, MasterCard, and Visa. We do not support using a "virtual" or pre-paid card as a payment type.

### What is K3s?

In 2019, SUSE (formally Rancher Labs) launched ‘K3s’ to create a seamless distribution of Kubernetes which aimed to have lighter system requirements and quicker start-up times when launching a cluster. Civo Kubernetes clusters are deployed as K3s clusters by default.

Read more about K3s [here](https://www.civo.com/blog/understanding-k3s).

### Should I use K3s or K8s?

K3s is a fully-compatible and full-featured Kubernetes. Its lighter resource overhead makes it ideal for smaller deployments, resource-limited settings, edge computing, or IoT, but given its simplified and opinionated setup, as well as lower resource consumption, it is a cost-effective choice for any number scenarios.

Upstream Kubernetes (K8s) is requires a cluster administrator to configure and manage a larger set of components in comparison to K3s. Traditionally, K8s is seen as suited for large-scale, intricate workloads needing high scalability, performance, and availability, which can all be configured by the administrator.

It's crucial to assess your specific needs, resources, and objectives, as both K3s and K8s have particular advantages, to make an informed choice.

Read more about the core differences between K3s and K8s [here](https://www.civo.com/blog/k8s-vs-k3s).

### What can I use k3s for?

Take a look at [this blog post](https://www.civo.com/blog/understanding-k3s) that explores use cases and the advantages K3s gives you. 

### What is Talos Linux?

Sidero Labs developed Talos Linux as a way to run Kubernetes consistently across all platforms, such as Edge, Cloud, Virtual, and Bare Metal. Talos Linux is a secured Linux distribution designed specifically for managing Kubernetes.

Read more about Talos Linux [here](https://www.civo.com/blog/introduction-talos-linux).

### Why does Civo use Talos Linux?

We have introduced the option of Talos Linux for our managed Kubernetes clusters. Talos Linux provides a more robust and customizable platform with advanced security features that allow for specialized use cases and strong security measures out of the box, and is designed to be a minimal platform purely for running Kubernetes.

