# Module 9 - Describe Features and Tools in Azure for Governance and Compliance

Status: ✅ Completed

## Exam Objective

Use Azure governance tools to enforce standards, control changes, and support compliance requirements.

## Core Definitions

- Governance: Organizational controls ensuring secure, consistent, and cost-effective cloud use.
- Azure Policy: Service that enforces rules and evaluates resource compliance.
- Initiative: Group of policies managed together for a governance objective.
- Compliance state: Result showing whether resources satisfy assigned policy requirements.
- Resource lock: Protection against accidental delete or modification.
- Tag: Key-value metadata assigned to resources for organization and reporting.
- Regulatory compliance: Alignment with standards and legal frameworks.

## Key Governance Tools

- Azure Policy and initiatives for preventive and detective control.
- Resource locks (`CanNotDelete`, `ReadOnly`) to protect critical resources.
- Tags for ownership, environment, cost center, and lifecycle management.
- Microsoft compliance offerings and dashboards for audit visibility.

## Policy vs RBAC (Commonly Asked)

- RBAC answers: who can do what.
- Policy answers: what is allowed to exist and how it must be configured.

## Practical Governance Patterns

- Enforce allowed regions or SKUs.
- Require tags at deployment.
- Deny public IP on sensitive workloads.
- Audit and remediate non-compliant resources.

## Common Exam Traps

- Locks do not replace backups or DR.
- Tags support organization and reporting but do not grant permissions.

## Quick Checklist

- [x] I can define policy, initiative, compliance, lock, and tag.
- [x] I can explain policy vs RBAC clearly.
- [x] I can map governance controls to risk/cost/compliance goals.
