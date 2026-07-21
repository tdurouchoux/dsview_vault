---
already_read: true
link: https://sinja.io/blog/data-landscape-guide-for-developers
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2026-07-22'
---

https://sinja.io/blog/data-landscape-guide-for-developers
## Summary

This guide provides a comprehensive overview of the data tools landscape for developers unfamiliar with data science workflows. It covers key concepts, tools, and processes across the data lifecycle, structured into four main sections:

**Flavors of Data Professions**
- Analytical type (e.g., data analysts, BI analysts): Focus on interpreting data, SQL, and BI tools like Tableau.
- Scientific type (e.g., data scientists): Build models and run experiments using Python (pandas, scikit-learn) and notebooks.
- Engineering type (e.g., data engineers): Build and maintain pipelines, databases, and infrastructure using tools like Apache Spark and cloud providers.
- Machine learning type: Focus on building and maintaining AI models, using tools like feature stores and ML frameworks.

**Data Lifecycle**
- **Storage**: File formats (CSV, Parquet, ORC, Avro), memory formats (Apache Arrow), and storage systems (data warehouses like Snowflake, data lakes, and lakehouses like Apache Iceberg).
- **Ingestion**: Extracting data from sources (databases, APIs, user events) using tools like Fivetran, Airbyte, and Debezium.
- **Processing**: Transforming data using languages (Python, SQL), batch vs. real-time processing, and tools like dbt, Spark, Flink, and Kafka.
- **Orchestration**: Managing pipelines with tools like Apache Airflow, Dagster, and Prefect.
- **Observability**: Monitoring pipelines and data quality with tools like Great Expectations, Monte Carlo, and Prometheus/Grafana.
- **Serving**: Delivering data to users via dashboards (Tableau, Power BI), operational analytics, embedded analytics, and ML use cases.

**Key Architectures and Concepts**
- **Medallion Architecture**: Organizing data into bronze (raw), silver (cleaned), and gold (aggregated) layers.
- **Dimensional Modeling**: Structuring data into fact and dimension tables for analytics.
- **Reverse ETL**: Loading processed data back into operational tools (e.g., CRM, support systems).
- **Semantic Layer**: Providing canonical definitions for business metrics and entities.
- **Data Lineage**: Tracking data transformations and dependencies.

**Data Consumption**
- Dashboards and reports (BI tools like Metabase, Looker).
- Operational analytics (syncing data to tools like HubSpot, Zendesk).
- Ad-hoc/exploratory analysis (notebooks like Jupyter, Deepnote).
- Embedded analytics (tools like Sisense, Luzmo).
- Data as a product (e.g., selling access to curated datasets).

The guide emphasizes the importance of understanding the data ecosystem, even for developers without a data background, to collaborate effectively with data teams. It avoids deep dives into tool-specific setups but provides a high-level map of the landscape.
## Links

- [Apache Parquet](https://en.wikipedia.org/wiki/Apache_Parquet) : Apache Parquet is a columnar storage file format optimized for use with big data processing frameworks. It is widely used in data lakes and warehouses for efficient data storage and retrieval.
- [Apache Arrow](https://en.wikipedia.org/wiki/Apache_Arrow) : Apache Arrow is an in-memory columnar data format designed for efficient data processing and interoperability between different tools and systems. It is commonly used for high-performance analytics and data exchange.
- [Apache Spark](https://spark.apache.org/) : Apache Spark is a distributed computing system designed for large-scale data processing. It provides an interface for programming entire clusters with implicit data parallelism and fault tolerance.
- [dbt (data build tool)](https://docs.getdbt.com/docs/introduction#dbt-core-engine) : dbt is a tool that enables data teams to transform raw data in their data warehouses into the desired shape for analysis. It allows for modular, SQL-based transformations and supports collaboration and documentation.
- [Apache Iceberg](https://iceberg.apache.org/) : Apache Iceberg is an open table format for huge analytic datasets. It brings reliability and simplicity to data lakes by providing ACID transactions, schema evolution, and time travel capabilities.

## Topics

![[topics/Concept/ETL Extract Transform Load]]

![[topics/Concept/ELT Extract Load Transform]]

![[topics/Concept/Data Warehouse]]

![[topics/Concept/Lakehouse]]

![[topics/Concept/Medallion Architecture]]

![[topics/Concept/Dimensional Modeling]]

![[topics/Concept/Data Lake]]

![[topics/Concept/Reverse ETL]]

![[topics/Concept/Data Observability]]

![[topics/Concept/Data Lineage]]