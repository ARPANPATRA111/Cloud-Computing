# Module 11 - Describe Monitoring Tools in Azure

Status: ⬜ Not Started

## Exam Objective

Understand Azure observability and health tooling to monitor resources, respond to incidents, and improve reliability.

## Core Definitions

- Monitoring: Collecting and analyzing telemetry to understand system behavior.
- Observability: Ability to infer internal system state from external signals.
- Metrics: Numeric time-series data (CPU, memory, request count, latency).
- Logs: Event and diagnostic records with rich detail.
- Alert: Rule-triggered notification when condition is met.
- Dashboard: Visual aggregation of key operational signals.

## Key Azure Monitoring Services

- Azure Monitor: Unified platform for metrics, logs, alerts, and dashboards.
- Log Analytics: Query and analysis engine for log data.
- Azure Alerts: Notification and action workflows based on metric/log conditions.
- Application Insights: App-level performance and diagnostic monitoring.
- Service Health: Information about Azure platform incidents affecting your services.
- Azure Advisor: Personalized recommendations for reliability, security, performance, and cost.

## Service Health vs Advisor

- Service Health: External platform status and incident communication.
- Advisor: Proactive optimization recommendations for your environment.

## Monitoring Workflow Basics

- Collect telemetry -> analyze trends -> configure alert thresholds -> trigger response actions.
- Effective alerts should be actionable, low-noise, and mapped to SLAs/SLOs.

## Common Exam Traps

- Governance tools enforce rules; monitoring tools observe runtime behavior.
- Service Health is not an application performance profiler.

## Quick Checklist

- [ ] I can define metrics, logs, alerts, and observability.
- [ ] I can explain Azure Monitor, Log Analytics, Service Health, and Advisor.
- [ ] I can distinguish monitoring from governance in exam scenarios.
