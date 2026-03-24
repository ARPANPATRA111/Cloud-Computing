# Module 10 - Describe Features and Tools for Managing and Deploying Azure Resources

Status: ✅ Completed

## Exam Objective

Recognize Azure management/deployment tools and choose the right one based on automation, scale, and environment.

## Core Definitions

- Azure Portal: Web-based GUI for interactive resource management.
- Azure CLI: Cross-platform command-line tool for scripting and automation.
- Azure PowerShell: PowerShell module set for Azure administration.
- ARM (Azure Resource Manager): Azure control plane and deployment model.
- ARM template: JSON-based declarative infrastructure definition.
- Bicep: Domain-specific language that compiles to ARM templates.
- Infrastructure as Code (IaC): Managing infrastructure with versioned code.
- Azure Arc: Manage non-Azure resources with Azure governance and tooling.

## Tool Selection Guide

- Use Portal for discovery, quick tasks, and learning.
- Use CLI/PowerShell for repeatable administration and automation.
- Use Bicep/ARM for consistent, version-controlled deployments.
- Use Arc for hybrid/multicloud governance consistency.

## Deployment Concepts

- Declarative model: Define desired end state, platform converges to that state.
- Idempotency: Running same deployment repeatedly should produce same result.
- Template-based deployment improves consistency, auditability, and rollback confidence.

## Common Exam Traps

- ARM is the deployment framework; Bicep is authoring language on top of ARM.
- CLI and PowerShell are management interfaces, not alternative cloud models.

## Quick Checklist

- [x] I can define Portal, CLI, PowerShell, ARM, Bicep, and IaC.
- [x] I can explain when to use interactive vs scripted vs declarative approaches.
- [x] I can explain Azure Arc at a fundamentals level.
