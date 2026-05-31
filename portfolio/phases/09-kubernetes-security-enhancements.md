# Optional Phase - Kubernetes Security Enhancements

**Status:** Not started  
**Roadmap phase:** Add only if the CKS market threshold is met  
**Related certification:** Certified Kubernetes Security Specialist  
**Related commercial offer:** EKS Platform Hardening Sprint  

## Decision Gate

Do not add this phase automatically. Use the
[CKS decision rule](../../roadmap/full-roadmap.md#74-cks-decision-rule) and
record the outcome in the [decision log](../../tracking/decision-log.md).

## Alignment

| Field | Notes |
|---|---|
| Business problem | Acme needs deeper Kubernetes workload-security controls if its EKS risk profile or market evidence justifies the additional investment. |
| Target audience | Platform-security engineer, security lead and Kubernetes platform team |
| Previous foundation | [Secure EKS GitOps Platform](04-secure-eks-gitops-platform.md) |
| Enables next | A stronger EKS hardening offer where Kubernetes-security demand is proven |
| Consulting angle | Show disciplined prioritisation: add deeper controls because evidence supports them, not because another certification exists. |

## Scope

### In Scope

- Admission-control policies
- Runtime-security concept and selected evidence
- Image-signing or verification concept
- Expanded image, dependency, SBOM and secrets scanning
- Workload-hardening notes
- Security-runbook updates
- Threat-model updates

### Out Of Scope

- Full production runtime-security deployment
- Every possible CKS domain as a portfolio feature
- Work that delays higher-priority SAP outcomes without market evidence

## Evidence Layers

### Executive Layer

- Short investment note: risk addressed, evidence for prioritisation and value
- Updated EKS hardening recommendations

### Architecture Layer

- Updated EKS security diagram
- ADR: admission-control approach
- Updated threat model

### Engineering Layer

- Demonstrable policy examples
- Selected CI/CD security gates
- Updated incident and remediation runbook
- Validation evidence

## Definition Of Done

- [ ] The decision to add CKS is evidence-based and logged.
- [ ] Selected policies and security gates are demonstrable.
- [ ] The EKS threat model and runbook are updated.
- [ ] The additional controls strengthen the EKS Hardening Sprint story.
- [ ] SAP timing remains protected or the trade-off is explicitly accepted.
