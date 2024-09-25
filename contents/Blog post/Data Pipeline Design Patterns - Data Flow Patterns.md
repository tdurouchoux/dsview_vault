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

2. **Source & Sink**: Defines sources (input systems) and sinks (output systems) and discusses critical aspects like source replayability (ability to retrieve historical data), source ordering (the sequence of data retrieval), and sink overwritability (ability to update existing data).

3. **Data Pipeline Patterns**: 
   - **Extraction Patterns**: 
     - Time ranged, Full Snapshot, Lookback, and Streaming methods for data retrieval.
   - **Behavioral Patterns**: 
     - Idempotent (ensures consistent output on multiple runs) and Self-healing (automatically processes missed data in subsequent runs).
   - **Structural Patterns**: 
     - Multi-hop pipelines (layered transformations), Conditional/Dynamic pipelines (complex flows based on conditions), and Disconnected pipelines (independent pipelines that complicate debugging and data lineage).

4. **Conclusion**: Summarizes the importance of consistent design patterns for effective communication and understanding among developers, recommending a flowchart for selecting appropriate designs based on requirements.

5. **Further Reading**: Suggests additional topics for deeper understanding, including data pipeline testing and building idempotent pipelines. 

Overall, the article provides a comprehensive overview of data pipeline design patterns, their advantages, and considerations for implementation.
## Links

1. [exponential backoff](https://learn.microsoft.com/en-us/dotnet/architecture/microservices/implement-resilient-applications/implement-retries-exponential-backoff) - A technique for handling retries in data pipelines to manage transient failures.
2. [watermarking](https://nightlies.apache.org/flink/flink-docs-master/docs/concepts/time/#event-time-and-watermarks) - A method used in stream processing to handle event time and late data.
3. [SCD2](https://www.startdataengineering.com/post/how-to-join-fact-scd2-tables/#what-is-an-scd2-table-and-why-use-it) - Explanation of Slowly Changing Dimensions Type 2, a common pattern in data warehousing.
4. [staging tables](https://www.startdataengineering.com/post/what-and-why-staging/#2-what-is-a-staging-area) - Overview of the purpose and use of staging tables in data pipelines.
5. [Medallion architecture from Databricks](https://docs.databricks.com/lakehouse/medallion.html) - A structured approach to organizing data in a lakehouse architecture for better data management.
## Topics

- [[topics/Concept/Data Pipeline]]
- [[topics/Concept/Source & Sink]]
- [[topics/Concept/Extraction Patterns]]
- [[topics/Concept/Behavioral Patterns]]
- [[topics/Concept/Structural Patterns]]