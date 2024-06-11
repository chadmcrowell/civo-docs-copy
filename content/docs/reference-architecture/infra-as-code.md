---
title: Infrastructure as Code on Civo
description: This diagram showcases a common setup on Civo cloud, built using infrastructure as code.
---


## Overview

This diagram showcases a common setup on Civo cloud, built using infrastructure as code tools.

![infra as code diagram](./images/civo-docs-infra-as-code-reference-architecture.png)

1. A developer submits their code to a Git Repo
2. The IaC code is reconciled with the tool
3. The tool authenticates to the Civo cloud account
4. The cloud resources are created (e.g. K8s Cluster & Civo Database) 