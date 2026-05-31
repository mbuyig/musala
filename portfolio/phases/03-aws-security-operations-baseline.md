# Phase 3 - AWS Security Operations Baseline

**Status:** Not started  
**Roadmap phase:** September-November 2026  
**Related certification:** AWS Certified Security Specialty  
**Related commercial offer:** AWS Security Baseline Review  

## Alignment

| Field | Notes |
|---|---|
| Business problem | Acme cannot consistently aggregate, triage and remediate security findings across AWS accounts. |
| Target audience | Security lead, cloud security engineer, platform lead and risk owner |
| Previous foundation | [Threat Model And Security Baseline](02-threat-model-security-baseline.md) |
| Enables next | A credible security-review offer and later governance reporting |
| Consulting angle | Connect security-service enablement to an operating model, priorities and cost implications. |

## Scope

### In Scope

- Security Hub aggregation
- GuardDuty across accounts
- AWS Config rule baseline
- Inspector enablement
- CloudTrail organisation-trail concept
- KMS baseline
- Findings triage model and remediation runbook
- Security dashboard concept
- Cost implications of security controls

### Out Of Scope

- Full SOC implementation
- Production alert routing and on-call integration
- SIEM procurement
- Automated remediation for every finding

## Evidence Layers

### Executive Layer

- Security-baseline findings report
- Prioritised remediation roadmap
- Summary of cost implications and operational ownership

### Architecture Layer

- Centralised security-services diagram
- Findings flow from detection to remediation
- ADR: delegated administrator and aggregation model
- ADR: which findings should be automated versus reviewed manually

### Engineering Layer

- Terraform or documented configuration for selected controls
- Example Config rules and KMS baseline
- Findings triage matrix
- Remediation runbook with ownership and severity model
- Validation evidence from the synthetic environment

## Ten-Minute Review Path

1. Read the findings report and remediation roadmap.
2. Inspect the security-services and findings-flow diagrams.
3. Review the triage matrix and one remediation-runbook example.
4. Inspect selected Terraform or configuration evidence.
5. Review the security-control cost notes.

## Definition Of Done

- [ ] The central security-services model is documented.
- [ ] Selected controls are demonstrable in the lab or through configuration.
- [ ] The triage matrix and remediation runbook exist.
- [ ] Findings map back to Phase 2 risks.
- [ ] Security-control costs and operating implications are documented.
- [ ] A one-page case study and 90-second talk track are complete.
