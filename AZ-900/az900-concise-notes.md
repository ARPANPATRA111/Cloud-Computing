# AZ-900 Concise Notes (From Transcript)

## 1) Exam Snapshot

- AZ-900 is a fundamentals exam focused on description-level understanding, not deep hands-on tasks.
- Typical exam profile: around 40-60 questions in roughly 60 minutes.
- Core verbs are usually "describe" and "identify".

## 2) Best Study Approach

- Use mixed prep: concise video + targeted reading + practice questions.
- Do not over-read everything end-to-end; focus on weak topics.
- Prioritize concept understanding over memorization.

## 3) Cloud Basics You Must Know

- Microsoft definition: cloud computing is delivery of computing services over the internet.
- Shared responsibility increases toward provider as you move from IaaS -> PaaS -> SaaS.
- Public cloud: fastest entry, high agility, pay-as-you-go.
- Private cloud: highest control and legacy support, but customer manages most responsibilities.
- Hybrid cloud: blend of both; common in enterprises with compliance/legacy constraints.

## 4) Cost and Consumption Concepts

- CapEx: upfront spend on physical infrastructure.
- OpEx: ongoing spend as you consume services.
- Cloud typically shifts spending toward OpEx.
- Consumption model means you pay for usage (time, transactions, storage, execution).
- Fixed/commitment pricing can improve cost predictability.

## 5) Serverless Essentials

- Serverless traits: stateless, ephemeral, event-triggered, pay-per-use.
- Azure Functions: event-driven code execution billed by usage.
- Azure Logic Apps: workflow automation with many built-in connectors.
- Azure Event Grid: push-based event routing (pub/sub style), avoids polling.

## 6) Core Benefit Terms (Commonly Confused)

- Availability: whether service is accessible.
- Uptime: whether underlying system is running.
- Reliability: ability to recover and continue functioning.
- Scalability: ability to handle growth.
- Elasticity: ability to auto-expand and shrink quickly based on demand.
- Predictability: expected performance and cost are known.

## 7) Security and Governance Basics

- Security in cloud is generally stronger due to provider scale and managed controls.
- Governance means rules/policies/guardrails for secure and compliant operations.
- Azure has built-in DDoS protection (basic) and enhanced options (standard tier).
- Cloud Adoption Framework gives structured guidance for governance and adoption.

## 8) Service Models (IaaS, PaaS, SaaS)

- IaaS: provider manages infrastructure, customer manages OS/apps/data.
  - Example use cases: test/dev, burst workloads, hybrid extension, disaster recovery.
- PaaS: provider manages more stack; customer focuses on app/data and business logic.
  - Example use cases: app development frameworks, analytics/BI services.
- SaaS: provider manages most of the stack; customer mainly configures and uses.
  - Example use cases: email, productivity suites, collaboration tools.

## 9) Azure Architecture Fundamentals

- Geography: broad market boundary.
- Region: one or more datacenters in a latency-defined area.
- Region pair: Microsoft-defined DR pairing, generally separated by large distance.
- Availability zone: physically separate zone in a region with independent power/network/cooling.
- Resource hierarchy: management group -> subscription -> resource group -> resource.

## 10) Azure Compute Essentials

- VMs: flexible IaaS compute.
- VM Scale Sets: automatic scaling of identical VM instances.
- Availability Sets: improve resilience across fault and update domains.
- Azure Virtual Desktop: desktop virtualization in Azure.
- Container Instances: simple, serverless containers without full orchestration.
- AKS: managed Kubernetes for orchestrated containers.
- App Service: host web apps, APIs, background jobs, and mobile backends.

## 11) Azure Networking Essentials

- VNet: logical private network boundary in Azure.
- Subnet: segmented IP range inside a VNet.
- VNet peering: private connectivity between VNets.
- VPN Gateway: encrypted tunnel over public internet to on-premises.
- ExpressRoute: private dedicated connectivity to Azure (not over public internet).
- Azure DNS: internal and external name resolution support.
- Public endpoint: internet-reachable service endpoint.
- Private endpoint: private IP-based access to PaaS resources from VNet/on-prem.

## 12) Quick Memory Triggers for Exam Day

- "Triggered + stateless + pay-per-use" -> think serverless (Functions/Event Grid).
- "Needs orchestration" -> AKS.
- "Simple container run, no orchestration" -> Container Instances.
- "Private dedicated connectivity" -> ExpressRoute.
- "Policy and guardrails" -> governance/Azure Policy.
