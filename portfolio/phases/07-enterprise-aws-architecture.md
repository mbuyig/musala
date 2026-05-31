# Phase 7 - Enterprise AWS Architecture

**Status:** Not started  
**Roadmap phase:** June-August 2027  
**Related certification:** AWS Solutions Architect Professional  
**Related commercial offer:** Cloud Cost, Security & Governance Assessment  

## Alignment

| Field | Notes |
|---|---|
| Business problem | Acme needs a joined-up architecture that scales the earlier platform patterns into an enterprise operating model. |
| Target audience | CTO, principal architect, security lead, platform lead and engineering leadership |
| Previous foundation | All earlier phases, especially landing zone, EKS, Terraform and FinOps |
| Enables next | Principal-level positioning and the formal governance framework |
| Consulting angle | Demonstrate architecture judgement across resilience, security, cost and organisational trade-offs. |

## Scope

### In Scope

- Executive summary and business context
- Account, network, identity and security architecture
- FinOps and observability architecture
- Disaster-recovery and backup strategies
- Migration strategy
- Cost model
- Well-Architected review
- Operational-readiness checklist
- Updated risk register
- ADR library
- Short trade-off papers

### Out Of Scope

- Production migration execution
- Exhaustive low-level design for every service
- Real client workload inventory
- A production-ready business-continuity exercise

## Evidence Layers

### Executive Layer

- Enterprise-architecture executive summary
- Prioritised roadmap and investment themes
- Risk, resilience and cost narrative for leadership

### Architecture Layer

- Joined-up enterprise AWS architecture diagram
- Identity, network, observability, DR and FinOps views
- ADR library
- Well-Architected review
- Trade-off papers:
  - cost versus resilience
  - centralised versus decentralised governance
  - security controls versus developer autonomy
  - EKS cost versus operational flexibility
  - multi-region resilience versus spend
  - NAT Gateway versus VPC endpoint trade-offs
  - Savings Plans versus flexibility
  - centralised versus distributed egress

### Engineering Layer

- References to demonstrable patterns from earlier phases
- Operational-readiness checklist
- Migration-wave example
- Recovery objectives and test assumptions

## Ten-Minute Review Path

1. Read the executive summary and prioritised roadmap.
2. Inspect the joined-up architecture diagram.
3. Review the Well-Architected findings.
4. Read two representative ADRs and one trade-off paper.
5. Review the DR strategy and operational-readiness checklist.

## Definition Of Done

- [ ] The enterprise architecture joins the earlier portfolio phases together.
- [ ] Executive, architecture and engineering views exist.
- [ ] DR, backup, migration, cost and observability approaches are documented.
- [ ] The Well-Architected review and updated risk register exist.
- [ ] At least four strong ADRs and four trade-off papers exist.
- [ ] A one-page case study and 90-second talk track are complete.
