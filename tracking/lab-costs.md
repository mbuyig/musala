# AWS Lab Costs

Track AWS lab spending and teardown discipline here. This protects the learning
budget and creates practical FinOps evidence.

The budget guidance and teardown rules are documented in the
[full roadmap](../roadmap/full-roadmap.md#23-aws-lab-budget-and-teardown-discipline).

## Monthly Spend

| Month | Planned Budget | Actual Spend | Difference | Unexpected Charges | Action Taken |
|---|---:|---:|---:|---|---|
| 2026-06 | £30-£60 |  |  |  |  |

## Weekly Teardown Checks

| Date | Terraform Stacks | EC2 | EKS | NAT Gateways | Load Balancers | EBS Volumes | Log Retention | Elastic IPs | Snapshots | Cost Explorer | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| YYYY-MM-DD | Checked | Checked | Checked | Checked | Checked | Checked | Checked | Checked | Checked | Checked |  |

## Unexpected Charges

| Date | Service | Amount | Cause | Resolution | Prevention |
|---|---|---:|---|---|---|
| YYYY-MM-DD |  |  |  |  |  |

## Monthly Review

At the end of each month:

- [ ] Compare actual spend with the planned budget.
- [ ] Explain any unexpected charges.
- [ ] Confirm that AWS Budgets and billing alerts are working.
- [ ] Review the most expensive services.
- [ ] Record one cost-control lesson or improvement.
