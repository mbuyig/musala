# Phase 2 - Threat Model And Security Baseline

**Status:** Not started  
**Roadmap phase:** August 2026  
**Related certification:** CompTIA Security+  
**Related commercial offer:** AWS Security Baseline Review  

## Alignment

| Field | Notes |
|---|---|
| Business problem | Acme has AWS foundations but lacks a documented view of threats, baseline controls and ownership. |
| Target audience | Security lead, platform lead, auditor and engineering manager |
| Previous foundation | [AWS Landing Zone Baseline](01-aws-landing-zone-baseline.md) |
| Enables next | Centralised AWS security operations and remediation priorities |
| Consulting angle | Translate technical controls into a risk-based baseline that a client can review and prioritise. |

## Scope

### In Scope

- Threat model for the fictional AWS platform
- Security baseline by control area
- IAM and SCP control mapping
- Risk register v1
- Basic incident-response roles and escalation flow
- Prioritised recommendations for the next phase

### Out Of Scope

- Exhaustive compliance audit
- Production penetration testing
- Complete incident-response programme
- Vendor-specific security-service implementation

## Evidence Layers

### Executive Layer

- One-page risk summary
- Top five risks with severity, owner and recommended action
- Short explanation of why the baseline matters to Acme's customers

### Architecture Layer

- Trust-boundary or data-flow diagram
- Threat model using a documented method such as STRIDE
- IAM and SCP control matrix
- Risk register v1

### Engineering Layer

- Example SCPs or policy snippets where useful
- Review checklist for IAM, logging and account boundaries
- Incident-response basics: detect, triage, contain, recover and learn
- Traceability between identified risks and planned controls

## Ten-Minute Review Path

1. Read the executive risk summary.
2. Inspect the trust-boundary diagram and top threats.
3. Review the IAM/SCP matrix and risk register.
4. Check the incident-response flow.
5. Identify which risks are handed into Phase 3.

## Definition Of Done

- [ ] The platform threat model is documented.
- [ ] The top risks are prioritised and assigned notional owners.
- [ ] IAM and SCP controls map back to risks.
- [ ] Incident-response basics are documented.
- [ ] Phase 3 recommendations are explicit.
- [ ] A one-page case study and 90-second talk track are complete.
