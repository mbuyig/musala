# Portfolio Evidence Index

Use this page to connect certifications to practical evidence. The goal is not
to collect credentials in isolation. Each major phase should produce a
demonstrable artefact, an architecture diagram, a
[case study](../templates/case-study.md), and an
[interview talk track](../templates/interview-talk-track.md).

Use only `Not started`, `In progress`, `Blocked`, or `Done` for status.

## Programme Documents

| Document | Purpose |
|---|---|
| [Acme Digital Services](acme-digital-services.md) | Fictional client context and transformation story |
| [Portfolio deliverables](deliverables.md) | Cross-phase alignment matrix and evidence model |
| [Phase briefs](phases/README.md) | Scoped definitions of done for each portfolio build |

## Certification Evidence Map

| Certification Or Phase | Evidence Artefact | Supporting Evidence | Status | Detailed Roadmap |
|---|---|---|---|---|
| AWS Solutions Architect Associate | [AWS Landing Zone Baseline](phases/01-aws-landing-zone-baseline.md) | Architecture diagram and initial cost assumptions | Not started | [Open](../roadmap/full-roadmap.md#june-july-2026-aws-solutions-architect-associate) |
| CompTIA Security+ | [Threat Model And Security Baseline](phases/02-threat-model-security-baseline.md) | SCP and IAM control mapping | Not started | [Open](../roadmap/full-roadmap.md#august-2026-comptia-security) |
| AWS Certified Security Specialty | [AWS Security Operations Baseline](phases/03-aws-security-operations-baseline.md) | Remediation runbook and security case study | Not started | [Open](../roadmap/full-roadmap.md#september-november-2026-aws-certified-security-specialty) |
| Certified Kubernetes Administrator | [Secure EKS GitOps Platform](phases/04-secure-eks-gitops-platform.md) | Incident runbook and EKS case study | Not started | [Open](../roadmap/full-roadmap.md#january-march-2027-certified-kubernetes-administrator) |
| Terraform Associate | [Terraform Module Framework](phases/05-terraform-module-framework.md) | CI validation and module documentation | Not started | [Open](../roadmap/full-roadmap.md#april-2027-terraform-associate-and-cks-decision-gate) |
| FinOps Certified Practitioner | [Cloud Cost Showback Model](phases/06-cloud-cost-showback-model.md) | Tagging policy, alerts and FinOps case study | Not started | [Open](../roadmap/full-roadmap.md#may-2027-finops-certified-practitioner) |
| AWS Solutions Architect Professional | [Enterprise AWS Architecture](phases/07-enterprise-aws-architecture.md) | ADR library, DR design and Well-Architected review | Not started | [Open](../roadmap/full-roadmap.md#june-august-2027-sap-portfolio-heavy-phase) |
| CCSP | [Cloud Governance Framework](phases/08-cloud-governance-framework.md) | Risk register and control mappings | Not started | [Open](../roadmap/full-roadmap.md#january-may-2028-ccsp) |
| CKS, if triggered | [Kubernetes Security Enhancements](phases/09-kubernetes-security-enhancements.md) | Runtime, admission-control and supply-chain evidence | Not started | [Open](../roadmap/full-roadmap.md#73-cks-triggered-path) |

## Evidence Layers

Each phase brief specifies three layers:

1. **Executive:** why the work matters, which risk or cost it addresses, and
   what outcome is expected.
2. **Architecture:** diagrams, decisions, trade-offs and control mappings.
3. **Engineering:** implementation, validation, runbooks and review guidance.

## Flagship Repository Shape

The intended portfolio structure is documented in the
[full roadmap](../roadmap/full-roadmap.md#111-recommended-structure). Keep the
main implementation coherent rather than creating many unfinished repositories.
