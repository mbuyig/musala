# Portfolio Deliverables

The portfolio is a single fictional client transformation programme for
[Acme Digital Services](acme-digital-services.md). Each phase improves the same
platform and creates evidence that supports both technical interviews and
consulting conversations.

## Evidence Model

Every major phase should include three layers:

| Layer | Purpose | Typical Evidence |
|---|---|---|
| Executive | Explain why the work matters | One-page summary, risk or cost outcome, recommendation |
| Architecture | Demonstrate judgement | Diagram, ADRs, control mapping, trade-off notes |
| Engineering | Demonstrate implementation depth | Terraform, configuration, validation, runbook, demo instructions |

Each major phase should also produce a
[case study](../templates/case-study.md), a
[portfolio README](../templates/portfolio-readme.md), and a 90-second
[interview talk track](../templates/interview-talk-track.md).

## Alignment Matrix

| Phase | Client Problem | Main Build | Consulting Artefacts | Commercial Alignment | Brief |
|---|---|---|---|---|---|
| SAA | Weak AWS foundations | Multi-account landing zone baseline | Diagram, ADRs, cost assumptions, case study | AWS Enterprise Landing Zone Build | [Open](phases/01-aws-landing-zone-baseline.md) |
| Security+ | Unclear risk posture | Threat model and control baseline | Risk register, control matrix, incident basics | AWS Security Baseline Review | [Open](phases/02-threat-model-security-baseline.md) |
| AWS Security Specialty | Fragmented detection and governance | Centralised security operations baseline | Findings report, dashboard concept, remediation runbook | AWS Security Baseline Review | [Open](phases/03-aws-security-operations-baseline.md) |
| CKA | Inconsistent Kubernetes operations | Secure EKS GitOps platform | Diagram, operating runbook, incident scenario | EKS Platform Hardening Sprint | [Open](phases/04-secure-eks-gitops-platform.md) |
| Terraform Associate | Repeated delivery patterns | Reusable Terraform module framework | Standards, CI evidence, module docs | AWS Enterprise Landing Zone Build | [Open](phases/05-terraform-module-framework.md) |
| FinOps Practitioner | Poor spend attribution | AWS cost showback and optimisation framework | Tagging policy, dashboard, executive cost report | Cloud Cost Optimisation Sprint | [Open](phases/06-cloud-cost-showback-model.md) |
| AWS SAP | Architecture scaling concerns | Enterprise AWS architecture v2 | ADR library, DR plan, trade-off papers, review | Cloud Cost, Security & Governance Assessment | [Open](phases/07-enterprise-aws-architecture.md) |
| CCSP | Weak executive governance | Cloud governance and security strategy framework | Risk register, mappings, policy pack, board report | Cloud Governance and Security Strategy Review | [Open](phases/08-cloud-governance-framework.md) |
| Optional CKS | Strong Kubernetes-security market demand | Kubernetes security enhancements | Policy evidence, threat notes, security runbook | EKS Platform Hardening Sprint | [Open](phases/09-kubernetes-security-enhancements.md) |

## Scope Control

Use the phase briefs as definitions of done. The goal is a small number of
convincing flagship assets, not production-scale infrastructure or a growing
backlog of unfinished experiments.

The actual implementation should live in a separate portfolio repository such
as:

```text
acme-cloud-platform/
```

This career-plan repository defines what to build and why. Link the completed
artefacts from [README.md](README.md) as they become available.
