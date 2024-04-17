---
title: Security Best Practices
description: Security Best Practices
---


## Overview

Civo recommends implementing security features and tools to secure your data and applications. These include firewalls, intrusion detection systems, encryption tools, and more. 

## Kubernetes Security Best Practices

Kubernetes is a complex container orchestration system that includes a control plane API, hosted on Linux servers in the cloud. With that in mind, there are many levels at which to implement strong security practices. Here are some of the most common approaches to securing your applications running on Kubernetes.

### Control Plane Security (Cluster Hardening)

Restrict access to the Kubernetes API by using strong authentication mechanisms like mutual TLS and integrated with an itendity provider. Also, take advantage of RBAC (Role-based Access Control) to limit permissions based on the principal of least privilege.

When using service accounts, exercise caution by rotating tokens regularly to prevent long-lived credentials. Also, limit token exposure to pods within the cluster and also to external environments outside the cluster. If this is a requirement, use encryption in-transit and at rest to encrypt tokens, so they aren't intercepted and stored in plain text for a potentially malicioius actor to find.

Update Kubernetes frequently to prevent as many vulnerabilities as possible. Kubernetes should be updated to the most recent stable versions to mitigate known vulnerabilities. It is recommended to create a disaster recovery plan and routinely test incident response in the event of a breach.
