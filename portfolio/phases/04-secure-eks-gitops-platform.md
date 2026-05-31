# Phase 4 - Secure EKS GitOps Platform

**Status:** Not started  
**Roadmap phase:** January-March 2027  
**Related certification:** Certified Kubernetes Administrator  
**Related commercial offer:** EKS Platform Hardening Sprint  

## Alignment

| Field | Notes |
|---|---|
| Business problem | Acme product teams need a repeatable EKS operating model that balances security, delivery speed and cost. |
| Target audience | Platform lead, Kubernetes engineer, security lead and product engineering teams |
| Previous foundation | [AWS Security Operations Baseline](03-aws-security-operations-baseline.md) |
| Enables next | EKS hardening offer, Terraform standardisation and optional CKS work |
| Consulting angle | Demonstrate platform judgement, not just cluster provisioning. |

## Scope

### In Scope

- Terraform-managed EKS cluster
- Argo CD or Flux GitOps workflow
- RBAC and IRSA
- Network policies and secrets-management approach
- Ingress, external DNS and certificate-management concepts
- Observability and logging
- Karpenter or Cluster Autoscaler notes
- Backup and restore approach
- Namespace and team cost-allocation model
- Synthetic suspicious-workload incident scenario
- Selected supply-chain checks such as image, SBOM, dependency or secrets scanning

### Out Of Scope

- Production multi-cluster fleet
- Complete service mesh
- Full runtime-security platform
- Production-grade disaster-recovery exercise

## Evidence Layers

### Executive Layer

- One-page EKS hardening summary
- Platform operating-model recommendation
- Cost and capacity considerations for decision-makers

### Architecture Layer

- EKS and GitOps architecture diagram
- RBAC and IRSA model
- ADR: GitOps tool choice
- ADR: node-scaling approach
- Security and cost trade-off notes

### Engineering Layer

- Terraform-managed cluster pattern
- GitOps repository structure
- Demonstrable policies and selected supply-chain checks
- Incident runbook: detect, triage, contain, remediate and review
- Namespace/team cost-allocation notes

## Ten-Minute Review Path

1. Read the EKS hardening summary.
2. Inspect the architecture diagram and operating model.
3. Review RBAC, IRSA and network-policy examples.
4. Walk through the suspicious-workload incident runbook.
5. Review capacity and cost-allocation notes.

## Definition Of Done

- [ ] The EKS GitOps platform pattern is demonstrable.
- [ ] RBAC, IRSA, network policies and secrets approach are documented.
- [ ] Observability, logging and backup approaches are explained.
- [ ] At least one supply-chain security control is demonstrated.
- [ ] The incident scenario and runbook are complete.
- [ ] EKS cost allocation and scaling trade-offs are documented.
- [ ] A one-page case study and 90-second talk track are complete.
