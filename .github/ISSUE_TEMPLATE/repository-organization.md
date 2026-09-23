---
name: Organize EKS and container repositories
about: Track catalog, topic, README, and maturity improvements
title: "Standardize and catalog EKS and container repositories"
labels: documentation
assignees: ""
---

## Goal

Create a consistent and discoverable portfolio for Amazon EKS, Kubernetes, containers, and related AI/ML platform-engineering repositories.

## Tasks

- [ ] Review the proposed repository classification in `catalog.json`
- [ ] Apply common topics to confirmed EKS repositories
- [ ] Apply container/serverless topics to adjacent repositories
- [ ] Review `LLM-inference` for meaningful EKS content
- [ ] Review `Durable_AIOperations` and add a README if appropriate
- [ ] Add descriptions to repositories currently missing them
- [ ] Add maturity status to every cataloged project
- [ ] Add architecture, prerequisites, cleanup, license, and security sections
- [ ] Cross-link related workshops and implementations
- [ ] Archive or clearly label abandoned experiments
- [ ] Run secret scanning before promoting repositories

## Baseline EKS topics

- `amazon-eks`
- `kubernetes`
- `containers`
- `aws`

Additional topics must reflect actual repository content.

## Safety

Do not place PATs, AWS credentials, kubeconfig files, Terraform state, account IDs, unredacted ARNs, Secret data, or raw diagnostic output in repositories or issues.
