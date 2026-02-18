# Module 7 — Databases 💾

Status: ✅ Completed

## Relational Databases on AWS

A **relational database** stores data in tables with rigid structures, relating different pieces of data to each other. You interact with these databases using **Structured Query Language (SQL)**.

### Ways to Run Relational Databases on AWS

1. **Unmanaged Solution (on EC2):** You can install a database directly onto an Amazon EC2 instance. This approach is preferable when you need **full control over the database and access to its underlying operating system**, including all installations and configurations.
2. **Amazon RDS (Relational Database Service):** This is a **fully managed service that helps set up, operate, and scale relational databases** in the cloud. RDS automates tasks like patching and backups, freeing you from routine maintenance.
3. **Amazon Aurora:** This is a fully managed, MySQL and PostgreSQL-compatible relational database built for the cloud. It is an excellent choice for **replacing high-cost commercial database engines** with a more cost-effective solution that still provides enterprise-level performance and reliability.

### Migrating Databases

**AWS Database Migration Service (DMS)** is a service designed to help you migrate databases to AWS easily and securely. Its key benefit is **minimizing application downtime**, as the source database remains fully operational during the migration process.

## NoSQL Databases: Amazon DynamoDB

**Amazon DynamoDB** is a **fully managed NoSQL key-value and document database that provides fast, predictable performance with seamless scalability**.

* **Flexible Schema:** The primary way NoSQL databases differ from relational databases is their use of **flexible schema designs rather than rigid table structures**. This is ideal for evolving datasets where not every item has the same attributes.
* **Performance:** DynamoDB is designed for high-traffic applications, offering single-digit millisecond performance at any scale.

## In-Memory Caching: Amazon ElastiCache

**In-memory caching** is a technique that stores frequently used data in memory (RAM) to improve application performance and reduce the need to fetch data from slower, disk-based storage.

**Amazon ElastiCache** is a fully managed in-memory caching service.

* **Primary Benefit:** Its core function is **improved application performance through in-memory caching**. By serving frequent read requests from memory, it reduces latency and offloads the primary database.

## Other Purpose-Built Databases

AWS recommends using purpose-built databases designed for specific workloads.

* **Amazon DocumentDB:** A document database service (MongoDB-compatible) that excels at handling semi-structured data. A practical use case is **storing and managing a large product catalog** for an e-commerce application.

* **Amazon Neptune:** A graph database service designed for **managing and querying highly connected datasets efficiently**, making it ideal for social networks, recommendation engines, and fraud detection.

## Backup and Shared Responsibility

### AWS Backup

**AWS Backup** is a centralized service that simplifies data backup. A key feature is its ability to provide **centralized backup policies and monitoring across multiple AWS accounts and Regions**, supporting a wide range of AWS services beyond just databases.

### Shared Responsibility for Managed Databases

When using fully managed AWS database services, the responsibilities are divided:

* **AWS is responsible for:** Managing the infrastructure, OS, patching, and backups.
* **You are responsible for:** **Designing your data structures and managing access controls** to protect your data.

## Summary

This module covered AWS's diverse database offerings. You learned about **relational (SQL) databases** on AWS, from an unmanaged approach on **EC2** to managed services like **Amazon RDS** and the cloud-native **Amazon Aurora**. You explored the flexibility of **NoSQL** with **Amazon DynamoDB**. You also saw how to improve database performance with **Amazon ElastiCache**. Finally, you were introduced to other purpose-built databases like **DocumentDB** and **Neptune**, the **AWS Database Migration Service**, and the centralized **AWS Backup** service.

## Resources

| Resource link | Description |
| :--- | :--- |
| [Amazon Relational Database Service (Amazon RDS)](https://aws.amazon.com/rds/) | A relational database service supporting multiple engines with automated maintenance and backups. |
| [Amazon RDS Security](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/security.html) | Detailed information about security configurations in Amazon RDS. |
| [Amazon Aurora](https://aws.amazon.com/rds/aurora/) | A cloud-native database offering superior performance and availability over traditional databases. |
| [AWS Database Migration Service (AWS DMS)](https://aws.amazon.com/dms/) | A service for seamless database migration while keeping the source database operational. |
| [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) | A NoSQL database service providing single-digit millisecond performance at any scale. |
| [Amazon ElastiCache](https://aws.amazon.com/elasticache/) | An in-memory caching service to improve application performance through faster data retrieval. |
| [Amazon DocumentDB](https://aws.amazon.com/documentdb/) | A MongoDB-compatible document database service designed for mission-critical workloads. |
| [Amazon Backup](https://aws.amazon.com/backup/) | A centralized service for automating and managing data backups across AWS services. |
| [Amazon Neptune](https://aws.amazon.com/neptune/) | A graph database service optimized for storing and querying highly connected data relationships. |
| [What Is a Relational Database?](https://aws.amazon.com/relational-database/) | A structured database using tables with predefined schemas, supporting complex queries via SQL. |
| [What Is a NoSQL Database?](https://aws.amazon.com/nosql/) | A nonrelational database offering flexible schemas and high scalability for varied data types. |
| [What Is an In-Memory Caching Service?](https://aws.amazon.com/caching/in-memory-caching/) | A high-speed data storage layer using RAM instead of disk storage for microsecond latency. |
| [AWS Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/) | AWS is responsible for security *of* the cloud, while customers are responsible for security *in* the cloud. |
