# Module 6 - Describe Azure Storage Services

Status: 🟡 In Progress

## Exam Objective

Choose the correct Azure storage service, tier, and redundancy model based on data pattern and recovery needs.

## Core Definitions

- Storage account: Top-level Azure object that contains storage services and settings.
- Blob storage: Object storage for unstructured data (images, videos, backups, logs).
- Azure Files: Managed file shares over SMB/NFS.
- Queue storage: Message storage for decoupled application communication.
- Table storage: NoSQL key-value store for semi-structured data.
- Managed disks: Block storage for Azure VMs.

## Access Tiers (Blob)

- Hot tier: Frequently accessed data; highest storage cost, lowest access cost.
- Cool tier: Infrequently accessed data; lower storage cost, higher access cost.
- Cold tier: Rarely accessed data; lower storage cost than cool, higher retrieval cost.
- Archive tier: Rarely accessed long-term retention; lowest storage cost, highest retrieval latency/cost.

## Quick Checklist

- [x] I can map workload type to Blob/File/Queue/Table/Disk correctly.
