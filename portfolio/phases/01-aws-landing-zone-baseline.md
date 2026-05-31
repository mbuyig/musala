# Phase 1 - AWS Landing Zone Baseline

**Status:** Not started  
**Roadmap phase:** June-July 2026  
**Related certification:** AWS Solutions Architect Associate  
**Related commercial offer:** AWS Enterprise Landing Zone Build  

## Alignment

| Field | Notes |
|---|---|
| Business problem | Acme needs a repeatable AWS foundation before more teams and workloads move into the platform. |
| Target audience | Platform lead, cloud architect, security lead and engineering manager |
| Previous foundation | Starting point for the portfolio |
| Enables next | Threat modelling, centralised security operations and enterprise architecture |
| Consulting angle | Establish the minimum viable AWS platform baseline without over-engineering the first iteration. |

## Scope

### In Scope

- Management, security, logging and shared-services account concepts
- Dev, test and prod workload account structure
- Baseline VPC design and network segmentation
- IAM role model and access assumptions
- Central logging model
- Tagging baseline and initial monthly cost assumptions
- Deployment and teardown guidance for lab components

### Out Of Scope

- Full AWS Control Tower implementation
- Production identity federation
- Production-grade hybrid connectivity
- Workload application deployment

## Evidence Layers

### Executive Layer

- One-page summary: why Acme needs a governed landing zone
- Account-purpose matrix with ownership and risk considerations
- Initial cost assumptions with notes on lab versus production scale

### Architecture Layer

- Multi-account architecture diagram
- Network diagram for the baseline VPC pattern
- ADR: account structure
- ADR: VPC and subnet model
- Notes on central logging and access boundaries

### Engineering Layer

- Terraform repository structure
- Demonstrable VPC, IAM, logging and shared-services baseline
- `terraform fmt`, `terraform validate` and security-scan evidence
- Deployment, review and teardown instructions

## Ten-Minute Review Path

1. Read the executive summary and account-purpose matrix.
2. Inspect the multi-account and VPC diagrams.
3. Review the two ADRs and the Terraform structure.
4. Run or inspect validation evidence.
5. Review the monthly cost assumptions and teardown guidance.

## Definition Of Done

- [ ] The fictional account model is documented.
- [ ] The VPC, IAM, logging and shared-services baseline is demonstrable.
- [ ] Architecture and network diagrams exist.
- [ ] Account-structure and VPC-design ADRs exist.
- [ ] Initial monthly cost assumptions are documented.
- [ ] Validation and security-scan results are recorded.
- [ ] A one-page case study and 90-second talk track are complete.
- [ ] A reviewer can understand the design and trade-offs in under 10 minutes.
