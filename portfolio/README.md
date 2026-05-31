# Portfolio Evidence Index

Use this page to connect certifications to practical evidence. The goal is not
to collect credentials in isolation. Each major phase should produce a
demonstrable artefact, an architecture diagram, a
[case study](../templates/case-study.md), and an interview talk track.

Use only `Not started`, `In progress`, `Blocked`, or `Done` for status.

## Certification Evidence Map

| Certification Or Phase | Evidence Artefact | Supporting Evidence | Status | Detailed Roadmap |
|---|---|---|---|---|
| AWS Solutions Architect Associate | [AWS Landing Zone Baseline](#aws-landing-zone-baseline) | Architecture diagram and initial cost assumptions | Not started | [Open](../roadmap/full-roadmap.md#june-july-2026-aws-solutions-architect-associate) |
| CompTIA Security+ | [Threat Model And Security Baseline](#threat-model-and-security-baseline) | SCP and IAM control mapping | Not started | [Open](../roadmap/full-roadmap.md#august-2026-comptia-security) |
| AWS Certified Security Specialty | [AWS Security Baseline](#aws-security-baseline) | Remediation runbook and security case study | Not started | [Open](../roadmap/full-roadmap.md#september-november-2026-aws-certified-security-specialty) |
| Certified Kubernetes Administrator | [Secure EKS GitOps Platform](#secure-eks-gitops-platform) | Incident runbook and EKS case study | Not started | [Open](../roadmap/full-roadmap.md#january-march-2027-certified-kubernetes-administrator) |
| Terraform Associate | [Terraform Module Framework](#terraform-module-framework) | CI validation and module documentation | Not started | [Open](../roadmap/full-roadmap.md#april-2027-terraform-associate-and-cks-decision-gate) |
| FinOps Certified Practitioner | [Cloud Cost Showback Model](#cloud-cost-showback-model) | Tagging policy, alerts and FinOps case study | Not started | [Open](../roadmap/full-roadmap.md#may-2027-finops-certified-practitioner) |
| AWS Solutions Architect Professional | [Enterprise AWS Architecture](#enterprise-aws-architecture) | ADR library, DR design and Well-Architected review | Not started | [Open](../roadmap/full-roadmap.md#june-august-2027-sap-portfolio-heavy-phase) |
| CCSP | [Cloud Governance Framework](#cloud-governance-framework) | Risk register and control mappings | Not started | [Open](../roadmap/full-roadmap.md#january-may-2028-ccsp) |
| CKS, if triggered | [Kubernetes Security Enhancements](#kubernetes-security-enhancements) | Runtime, admission-control and supply-chain evidence | Not started | [Open](../roadmap/full-roadmap.md#73-cks-triggered-path) |

## Evidence Artefacts

### AWS Landing Zone Baseline

**Planned evidence:** Multi-account AWS landing zone baseline with Terraform
VPC, IAM, logging and shared-services patterns.

### Threat Model And Security Baseline

**Planned evidence:** Threat model, security baseline and SCP/IAM control
mapping for the fictional enterprise platform.

### AWS Security Baseline

**Planned evidence:** Security Hub aggregation, GuardDuty, AWS Config,
Inspector, CloudTrail, KMS baseline and a remediation runbook.

### Secure EKS GitOps Platform

**Planned evidence:** EKS platform with RBAC, IRSA, network policies,
observability, secrets management and an incident scenario.

### Terraform Module Framework

**Planned evidence:** Reusable Terraform modules with CI validation,
documentation and security scanning.

### Cloud Cost Showback Model

**Planned evidence:** Tagging policy, budgets, cost allocation model, showback
dashboard and FinOps case study.

### Enterprise AWS Architecture

**Planned evidence:** Enterprise architecture v2, ADRs, DR design,
Well-Architected review and cost/security/governance trade-off documents.

### Cloud Governance Framework

**Planned evidence:** Risk register, NIST/ISO/CIS control mapping, FinOps
governance model and executive strategy pack.

### Kubernetes Security Enhancements

**Planned evidence:** Optional CKS-driven runtime security, admission control
and supply-chain security enhancements when the market threshold is met.

## Flagship Repository Shape

The intended portfolio structure is documented in the
[full roadmap](../roadmap/full-roadmap.md#111-recommended-structure). Keep the
main implementation coherent rather than creating many unfinished repositories.
