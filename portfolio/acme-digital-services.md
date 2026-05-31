# Acme Digital Services

This fictional organisation provides a consistent client context for the entire
portfolio. The aim is to show a coherent transformation programme rather than a
collection of unrelated certification labs.

## Organisation Profile

| Field | Fictional Context |
|---|---|
| Organisation | Acme Digital Services |
| Business model | UK-based engineering-led digital services company |
| Size | Approximately 800 staff across product, engineering and operations |
| Customer profile | Enterprise and regulated-sector customers |
| Platform | AWS-first with containerised services and a growing EKS footprint |
| Delivery model | Multiple product teams supported by a central platform team |
| Primary concerns | Security, auditability, cloud cost visibility, resilience and developer enablement |

## Starting Position

Acme has grown quickly. Product teams can ship services, but the platform has
accumulated inconsistent patterns:

- AWS accounts have unclear ownership and uneven controls.
- Networking, IAM and logging patterns are not consistently documented.
- Security findings are fragmented across accounts.
- Terraform modules and validation practices vary between teams.
- EKS adoption is increasing without a standard operating model.
- Cloud costs are visible at account level but difficult to attribute to teams.
- Architecture decisions are often implicit rather than recorded.
- Executives do not receive a joined-up view of cloud risk, cost and maturity.

## Transformation Goal

Create a governed AWS and Kubernetes platform operating model that:

- gives product teams repeatable delivery patterns
- improves security visibility and remediation
- makes cloud spending attributable and reviewable
- documents architecture trade-offs
- supports audit and executive reporting
- balances central governance with developer autonomy

## Constraints

- Use synthetic data and fictional account identifiers only.
- Keep lab infrastructure affordable and short-lived.
- Prefer demonstrable patterns over a production-sized deployment.
- Explain where a real client implementation would require deeper discovery.
- Treat security, cost and operability as architecture concerns from the start.

## Transformation Story

| Phase | Transformation Step |
|---:|---|
| 1 | Establish multi-account AWS foundations. |
| 2 | Document threats, risks and baseline controls. |
| 3 | Centralise AWS security operations and remediation. |
| 4 | Introduce a secure EKS GitOps platform pattern. |
| 5 | Standardise Terraform module delivery and validation. |
| 6 | Add cost allocation, showback and optimisation processes. |
| 7 | Bring the platform together as an enterprise architecture. |
| 8 | Formalise governance, reporting and control mappings. |
| Optional | Deepen Kubernetes security controls if market evidence supports CKS. |

## Portfolio Safety Boundary

The Acme platform is deliberately fictional. Do not copy employer or client
architectures, account structures, internal names, incidents, security
exceptions, policies or diagrams. Rebuild general patterns in a synthetic
environment and explain their real-world relevance without exposing sensitive
information.
