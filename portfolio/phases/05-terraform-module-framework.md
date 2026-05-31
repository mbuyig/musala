# Phase 5 - Terraform Module Framework

**Status:** Not started  
**Roadmap phase:** April 2027  
**Related certification:** Terraform Associate  
**Related commercial offer:** AWS Enterprise Landing Zone Build  

## Alignment

| Field | Notes |
|---|---|
| Business problem | Acme teams repeat infrastructure patterns inconsistently and need a reliable path for shared Terraform modules. |
| Target audience | Platform engineers, cloud engineers, security engineers and technical leads |
| Previous foundation | Modules and patterns created during the landing-zone and EKS phases |
| Enables next | Faster delivery, stronger validation and maintainable enterprise architecture |
| Consulting angle | Show how platform governance becomes a paved road rather than a document-only exercise. |

## Scope

### In Scope

- Module versioning and release approach
- Documentation and usage examples
- Remote-state pattern
- CI validation
- `terraform fmt`, `terraform validate` and `tflint`
- `checkov` or `tfsec`
- Pre-commit hooks
- Cost-estimation concept where useful

### Out Of Scope

- Large public module registry
- Backward compatibility for every hypothetical consumer
- Full platform migration to the new framework

## Evidence Layers

### Executive Layer

- Short summary of delivery risk reduced by standard modules
- Explanation of governance benefits and adoption trade-offs

### Architecture Layer

- Module-consumption and release-flow diagram
- ADR: module boundaries
- ADR: versioning and release strategy

### Engineering Layer

- Reusable module examples
- CI workflow and pre-commit configuration
- Validation and security-scan output
- Module README and adoption guidance

## Ten-Minute Review Path

1. Read the standardisation summary.
2. Inspect the module and release-flow diagram.
3. Review one module README and example.
4. Inspect the CI workflow and scan output.
5. Review module-boundary and versioning ADRs.

## Definition Of Done

- [ ] At least one reusable module is documented and demonstrable.
- [ ] CI runs formatting, validation, linting and security checks.
- [ ] Versioning and release guidance exist.
- [ ] Remote-state and cost-estimation considerations are documented.
- [ ] Adoption trade-offs are clear.
- [ ] A one-page case study and 90-second talk track are complete.
