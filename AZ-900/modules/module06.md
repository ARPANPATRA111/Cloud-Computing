# Module 6 - Describe Azure Storage Services

Status: ✅ Completed

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

## Redundancy Definitions

- LRS (Locally Redundant Storage): Multiple copies in one datacenter.
- ZRS (Zone-Redundant Storage): Copies across availability zones in a region.
- GRS (Geo-Redundant Storage): Replication to paired secondary region.
- GZRS (Geo-Zone-Redundant Storage): Zone redundancy in primary plus geo replication.

## Data Movement and Migration Tools

- AzCopy: Command-line tool for high-performance data copy.
- Storage Explorer: GUI tool for managing blobs/files/queues/tables.
- Azure File Sync: Synchronizes on-prem Windows file servers with Azure Files.
- Azure Migrate: Discovery, assessment, and migration planning platform.
- Azure Data Box: Physical transfer appliance for large-volume offline data transfer.

## Common Exam Traps

- Blob is for unstructured object data, not traditional file share semantics.
- Archive is offline-like with higher retrieval delay, not for active workloads.
- LRS and ZRS do not provide cross-region protection.

## Quick Checklist

- [x] I can map workload type to Blob/File/Queue/Table/Disk correctly.
- [x] I can choose hot/cool/cold/archive by access pattern.
- [x] I can explain LRS, ZRS, GRS, and GZRS accurately.
