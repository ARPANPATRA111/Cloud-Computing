# Module 5 - Describe Azure Compute and Networking Services

Status: ✅ Completed

## Exam Objective

Identifing the right Azure compute and networking service from scenario wording.

## Compute Definitions

- Azure Virtual Machines (VMs): IaaS virtualized servers where you manage OS and software.
- VM Scale Sets: Group of identical VMs that scale automatically.
- Availability Sets: VM grouping that improves resilience via update and fault domains.
- Azure App Service: PaaS hosting for web apps, APIs, and background workloads.
- Azure Functions: Serverless event-driven compute executing code on trigger.
- Azure Container Instances (ACI): Run containers quickly without managing orchestrator.
- Azure Kubernetes Service (AKS): Managed Kubernetes cluster for container orchestration.
- Azure Virtual Desktop (AVD): Cloud-hosted virtual desktop and app delivery service.

## Networking Definitions

- Virtual Network (VNet): Private logical network in Azure.
- Subnet: Segmented IP address range inside a VNet.
- Network Security Group (NSG): Layer 4 inbound/outbound allow/deny rule set.
- VNet peering: Private connection between VNets using Azure backbone.
- VPN Gateway: Encrypted tunnel over internet between Azure and on-prem/VNet.
- ExpressRoute: Private dedicated connection to Azure that bypasses public internet.
- Azure DNS: DNS hosting and resolution service.
- Public endpoint: Internet-accessible service endpoint.
- Private endpoint: Private IP access to PaaS resources from VNet.

## Service Selection Guide

- Need full OS control -> VM.
- Need rapid web/API hosting with minimal ops -> App Service.
- Need event-triggered, usage-billed code -> Functions.
- Need simple containers quickly -> ACI.
- Need container orchestration -> AKS.
- Need desktop virtualization -> AVD.
- Need private, high-consistency enterprise connectivity -> ExpressRoute.
- Need hybrid quickly over internet -> VPN Gateway.

## Common Exam Traps

- VNet peering is VNet-to-VNet, not on-prem connectivity.
- ExpressRoute is private connectivity, not just "faster VPN" wording.
- NSG filters traffic; it is not a full enterprise firewall replacement.

## Quick Checklist

- [x] I can define each compute option and when to use it.
- [x] I can differentiate peering, VPN Gateway, and ExpressRoute.
- [x] I can explain public endpoint vs private endpoint.
