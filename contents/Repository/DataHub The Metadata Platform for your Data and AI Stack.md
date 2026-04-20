---
already_read: true
link: https://github.com/datahub-project/datahub
read_priority: 0
relevance: 5
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-04-20'
---

https://github.com/datahub-project/datahub
## Summary

DataHub is an open-source metadata platform for data discovery, governance, and observability, originally built at LinkedIn. It acts as a central metadata hub for fragmented data stacks, supporting real-time updates and AI agent integrations via Model Context Protocol (MCP).

Key features:
- **Real-time metadata streaming** (Kafka-based) and **80+ connectors** (Snowflake, BigQuery, dbt, etc.).
- **AI-ready**: MCP server enables natural language queries (e.g., "Show lineage for this table") in IDEs like Cursor or Claude.
- **Governance & lineage**: Track data flow, ownership, and compliance with custom properties.
- **Deployment options**: Managed SaaS, Docker, or Kubernetes (Helm).
- **Developer tools**: Python/Java SDKs, GraphQL/REST APIs, and CLI.

Use cases include data discovery, impact analysis, governance, and AI agent context management. Trusted by 3,000+ organizations (e.g., Netflix, Visa, Optum). Apache 2.0 licensed. Docs: [datahub.com/docs](https://docs.datahub.com).
## Links

- [DataHub Official Documentation](https://docs.datahub.com) : Comprehensive documentation for DataHub, including architecture, APIs, installation guides, and feature details.
- [DataHub Quickstart Guide](https://docs.datahub.com/docs/quickstart) : Step-by-step guide to quickly set up and run DataHub locally or via Docker, including prerequisites and basic configurations.
- [DataHub Architecture Overview](https://docs.datahub.com/docs/architecture/architecture) : Detailed breakdown of DataHub's architecture, including streaming-first design, API-first approach, and scalability considerations.
- [DataHub Metadata Ingestion Guide](https://docs.datahub.com/docs/metadata-ingestion) : Guide on how to ingest metadata from various sources (e.g., Snowflake, BigQuery) into DataHub, including configuration examples and expected outputs.
- [DataHub Lineage Feature Guide](https://docs.datahub.com/docs/features/feature-guides/lineage) : Documentation on DataHub's lineage capabilities, including how to query and visualize upstream/downstream dependencies for datasets.

## Topics

![[topics/Platform/DataHub]]

![[topics/Concept/Metadata Management]]

![[topics/Concept/Data Lineage]]

![[topics/Concept/Data Discovery]]

![[topics/Library/acryl datahub]]

![[topics/Concept/Metadata Graph]]

![[topics/Concept/Data Governance]]

![[topics/Concept/Model Context Protocol MCP]]

![[topics/Concept/Data Contracts]]