---
already_read: false
link: https://www.startdataengineering.com/post/design-patterns/
read_priority: 1
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2023-01-12'
---

https://www.startdataengineering.com/post/design-patterns/
## Summary

The article discusses data pipeline design patterns, focusing on data flow patterns essential for building robust data pipelines. Key sections include:

1. **Introduction**: Emphasizes the importance of solid design foundations to prevent flaky pipelines and introduces the concept of data flow patterns.

2. **Source & Sink**: Defines sources (input systems) and sinks (output systems) and discusses:
   - **Source Replayability**: The ability to retrieve historical data.
   - **Source Ordering**: The necessity of maintaining the order of data.
   - **Sink Overwritability**: The ability to update existing data without creating duplicates.

3. **Data Pipeline Patterns**: Categorizes patterns into:
   - **Extraction Patterns**: Methods for pulling data, including time ranged, full snapshot, lookback, and streaming.
   - **Behavioral Patterns**: How pipelines handle failures, focusing on idempotent and self-healing designs.
   - **Structural Patterns**: Organization of tasks, including multi-hop, conditional/dynamic, and disconnected pipelines.

4. **Conclusion**: Summarizes the importance of consistent design patterns for effective communication and understanding among developers, suggesting a flowchart for selecting appropriate designs.

5. **Further Reading**: Provides resources for deeper exploration of related topics.

The article serves as a guide for data engineers to choose and implement effective data pipeline designs based on specific use cases and requirements.
## Links

1. [dbt docs](https://docs.getdbt.com/docs/build/projects) - Documentation for dbt, a tool for transforming data in your warehouse, which is relevant for building data pipelines.
2. [Databricks docs](https://docs.databricks.com/lakehouse/medallion.html) - Documentation on the Medallion architecture from Databricks, which is a structural pattern for organizing data flows in pipelines.
3. [How to backfill SQL query using Apache Airflow](https://www.startdataengineering.com/post/how-to-backfill-sql-query-using-apache-airflow/#what-is-backfilling-) - A guide on backfilling data in pipelines using Apache Airflow, relevant for managing historical data.
4. [What and why staging](https://www.startdataengineering.com/post/what-and-why-staging/#2-what-is-a-staging-area) - An article explaining the concept of staging areas in data pipelines, which is crucial for data organization and processing.
5. [How to add tests to your data pipeline](https://www.startdataengineering.com/post/how-to-add-tests-to-your-data-pipeline/) - A guide on implementing testing in data pipelines, which is essential for ensuring data quality and reliability.
## Topics

![](topics/Concept/Data%20Pipeline%20Design%20Patterns)

![](topics/Concept/Source%20Sink)

![](topics/Concept/Extraction%20Patterns)

![](topics/Concept/Behavioral%20Patterns)

![](topics/Concept/Structural%20Patterns)