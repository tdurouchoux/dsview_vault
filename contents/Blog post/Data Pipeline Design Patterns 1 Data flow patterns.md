---
already_read: false
link: https://www.startdataengineering.com/post/design-patterns/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2023-01-12'
---

https://www.startdataengineering.com/post/design-patterns/
## Summary

The article discusses various data pipeline design patterns, focusing on data flow patterns that help enhance data pipeline robustness and efficiency. Key sections include:

1. **Source & Sink**: Defines the core concepts of sources (input systems) and sinks (output systems). Key considerations include replayability of sources, ordering of data, and overwritability of sinks, impacting how data can be retrieved and processed.

2. **Data Pipeline Patterns**: 
   - **Extraction Patterns**:
     - Time ranged, Full Snapshot, Lookback, and Streaming methods for pulling data.
   - **Behavioral Patterns**:
     - Idempotent and Self-healing patterns to manage failures and reruns. Idempotency ensures consistent output from repeated runs, while self-healing adapts to errors by catching up on missed data.
   - **Structural Patterns**:
     - Multi-hop pipelines maintain data cleanliness across transformations. Conditional pipelines adapt tasks based on execution context, and Disconnected pipelines complicate debugging and SLAs due to interdependencies.

3. **Conclusion**: Emphasizes the importance of consistent design patterns to facilitate communication and understanding among developers. Encourages careful selection of the simplest applicable design when constructing new pipelines.

Further reading options are provided for those interested in delving deeper into specific related topics such as data pipeline testing, SCD2 tables, and building idempotent pipelines.
## Links

- [Data Warehouse Overview](https://www.startdataengineering.com/post/what-is-a-data-warehouse/#3-what-is-a-data-warehouse) : An overview of data warehousing concepts, ideal for understanding the context in which data pipelines operate.
- [Event Time and Watermarks in Apache Flink](https://nightlies.apache.org/flink/flink-docs-master/docs/concepts/time/#event-time-and-watermarks) : Documentation on handling event time and watermarks, which are crucial for ensuring the order of events in data streams.
- [Best Practices for Structuring DBT Projects](https://docs.getdbt.com/guides/best-practices/how-we-structure/1-guide-overview) : Guidance on how to effectively structure and manage DBT projects to streamline data pipeline development.
- [How to Build Idempotent Pipelines](https://www.startdataengineering.com/post/why-how-idempotent-data-pipeline/) : A guide on creating idempotent data pipelines, ensuring consistency and reliability in data processing.
- [Medallion Architecture in Databricks](https://docs.databricks.com/lakehouse/medallion.html) : An overview of the medallion architecture for data pipelines in Databricks, outlining its structure and benefits.

## Topics

![](topics/Concept/Data%20Pipeline%20Design%20Patterns)

![](topics/Concept/Source%20and%20Sink)

![](topics/Concept/Idempotency)

![](topics/Concept/Self%20Healing%20Pipelines)

![](topics/Concept/Extraction%20Patterns)

![](topics/Concept/Data%20Pipeline%20Behavior%20under%20Failure)

![](topics/Concept/Disconnected%20Data%20Pipelines)

![](topics/Concept/Multi%20hop%20Data%20Pipelines)