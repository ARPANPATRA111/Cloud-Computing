# Module 4 - Describe Core Architectural Components of Azure

Status: ✅ Completed

## Exam Objective

Will see Azure global infrastructure, physical/logical hierarchy, and resource organization so you can select the right scope for deployment, governance, and resilience.

## Core Definitions

- Azure geography: A market area containing one or more Azure regions, often aligned to data residency and compliance boundaries.
- Azure region: One or more datacenters in a specific location connected through low-latency networking.
- Region pair: Two Azure regions in the same geography paired by Microsoft for disaster recovery and platform resiliency.
- Sovereign region: A specially isolated region designed for strict legal, regulatory, or government requirements.
- Availability zone: A physically separate datacenter location within a region, each with independent power, cooling, and networking.
- Datacenter: Physical facility hosting servers, storage, and network infrastructure.
- Resource: Any manageable Azure object such as VM, VNet, storage account, or Key Vault.
- Resource group: Logical container for related resources that share a similar lifecycle.
- Subscription: Billing, quota, and management boundary for Azure resources.
- Management group: Governance layer above subscriptions used for policy and access inheritance.

## Azure Hierarchy (Must Memorize)

- Management group -> Subscription -> Resource group -> Resource.

## How to Choose the Right Scope

- Use management groups when multiple subscriptions need common policy and governance.
- Use subscriptions to separate billing, environments, business units, or strong isolation boundaries.
- Use resource groups to organize resources by workload lifecycle (create/update/delete together).
- Use resource-level controls when only specific resources need unique permissions or policy exceptions.

## Regions, Region Pairs, and Availability Zones

- Choose region based on latency, service availability, compliance constraints, and cost.
- Region pairs are Microsoft-defined, not user-defined.
- Availability zones protect against datacenter-level failures within one region.
- Cross-region designs improve disaster recovery posture beyond single-region failures.

## AZ-900 Exam-Oriented Comparisons

- Region vs availability zone: Region is a broad location containing one or more datacenters; availability zone is a physically separate zone inside a region.
- Subscription vs resource group: Subscription is the billing and quota boundary; resource group is the workload organization boundary.
- Policy scope: Higher-level assignment (management group/subscription) applies broadly, while lower-level assignment (resource group/resource) is more targeted.

## Common Exam Traps

- Resource groups are not billing boundaries; subscriptions are.
- Availability zones are within a region, not multiple regions.
- Region pairing is controlled by Azure platform design.
- Not every Azure service is available in every region.

## Quick Checklist

- [x] I can define geography, region, region pair, sovereign region, and availability zone.
- [x] I can explain Azure hierarchy in the right order.
- [x] I can choose management group vs subscription vs resource group by scenario.
- [x] I can explain when to use zones and when to use multiple regions.

## 1-Minute Revision

- Think top-down: govern at management group, bill at subscription, organize in resource groups, deploy as resources.
- Think resilience: zones for datacenter faults, region pairs/multi-region for larger outages.
- Think exam clues: billing -> subscription, lifecycle grouping -> resource group, broad governance -> management group.
