---
already_read: false
link: https://polaris.apache.org/releases/1.2.0/
read_priority: 3
relevance: 0
source: null
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2025-11-05'
---

https://polaris.apache.org/releases/1.2.0/
## Summary

Apache Polaris is an open-source catalog implementation for Apache Iceberg tables, built on the Iceberg REST protocol. It provides centralized, secure read and write access to Iceberg tables across different REST-compatible query engines.

Key concepts include:

- **Catalog**: Organizes Iceberg tables and can be internal (managed by Polaris) or external (managed by another provider, read-only in Polaris). Catalogs are configured with storage settings for S3, Azure, or Google Cloud Storage.
- **Namespace**: Logically groups Iceberg tables within a catalog, with support for nested namespaces.
- **Storage Configuration**: Stores IAM entities for cloud storage, enabling secure connections between Polaris and the storage provider.

Security and access control features include:

- **Credential Vending**: Provides temporary storage credentials to query engines during execution.
- **Identity and Access Management (IAM)**: Securely connects Polaris to storage for table data and metadata.
- **Role-Based Access Control (RBAC)**: Enforces access control across all tables, with principal roles and catalog roles for delegating privileges.

Polaris supports deployment on various cloud providers (AWS, Azure, GCP, MinIO) and integrates with tools like Keycloak for identity management and telemetry tools for monitoring. It also offers a Spark client, Helm chart for Kubernetes deployment, and support for Iceberg REST and Hive metastore federation.
## Links

- [Apache Iceberg REST Catalog Specification](https://iceberg.apache.org/rest-catalog-spec/) : This link points to the Apache Iceberg REST Catalog Specification, which is relevant for understanding the technical specifications of the Iceberg REST protocol that Polaris is built upon.
- [Apache Iceberg Specification Overview](https://iceberg.apache.org/spec/#overview) : This link points to the Apache Iceberg Specification Overview, which provides an overview of the Iceberg table format and its specifications, relevant for understanding the foundational technology that Polaris is built on.

## Topics

![[topics/Concept/Role Based Access Control RBAC]]

![[topics/Tool/Apache Polaris]]

![[topics/Library/Apache Iceberg]]