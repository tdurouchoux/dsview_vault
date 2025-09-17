---
already_read: false
link: https://www.startdataengineering.com/post/design-patterns/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
- Data_Analysis
type: Content
upload_date: '2023-01-12'
---

https://www.startdataengineering.com/post/design-patterns/
## Summary

The content discusses data pipeline design patterns, focusing on data flow patterns. It begins by emphasizing the importance of solid data pipeline design foundations to prevent flakiness over time. The post is structured into several sections:

1. **Introduction**: It sets the stage for understanding data pipeline design patterns, their pros and cons, and when to use them.

2. **Source & Sink**: This section explains the importance of understanding the inputs (sources) and outputs (sinks) of a data pipeline. It covers:
   - **Source Replayability**: The ability of a source system to provide historical data.
   - **Source Ordering**: The order in which data is pulled from a source system.
   - **Sink Overwritability**: The ability of a sink system to update specific rows of existing data.

3. **Data Pipeline Patterns**: This section is divided into three main categories:
   - **Extraction Patterns**: Methods for pulling data from a source, including time-ranged, full snapshot, lookback, and streaming.
   - **Behavioral Patterns**: How data pipelines behave in case of failures and reruns, including idempotent and self-healing pipelines.
   - **Structural Patterns**: How tasks/transformations are structured in a data pipeline, including multi-hop pipelines, conditional/dynamic pipelines, and disconnected data pipelines.

4. **Conclusion**: Summarizes the typical design patterns for organizing data flows through a pipeline and emphasizes the importance of using consistent patterns.

5. **Further Reading**: Provides additional resources for readers interested in learning more about data pipeline design patterns.

6. **References**: Lists the sources and tools referenced in the article.

The article aims to help data engineers choose the right design patterns for their data pipelines by providing a comprehensive overview of the most common patterns and their use cases.
## Links

- [How to build idempotent pipelines](https://www.startdataengineering.com/post/why-how-idempotent-data-pipeline/) : This link describes how to build idempotent pipelines, which are crucial for ensuring that running a data pipeline multiple times with the same input does not change the output. It provides insights into the implementation and benefits of idempotency in data pipelines.
- [Data pipeline testing](https://www.startdataengineering.com/post/how-to-add-tests-to-your-data-pipeline/) : This link provides information on how to add tests to your data pipeline. It covers various testing strategies and techniques to ensure the reliability and accuracy of data pipelines.
- [What is an SCD2 table](https://www.startdataengineering.com/post/how-to-join-fact-scd2-tables/#what-is-an-scd2-table-and-why-use-it) : This link explains what an SCD2 (Slowly Changing Dimension Type 2) table is and why it is used. It is relevant for understanding how to manage historical data changes in data warehousing.
- [What is a staging area](https://www.startdataengineering.com/post/what-and-why-staging/#2-what-is-a-staging-area) : This link describes what a staging area is and its importance in the ETL (Extract, Transform, Load) process. It helps in understanding the role of staging areas in data integration and transformation.
- [What is a data warehouse](https://www.startdataengineering.com/post/what-is-a-data-warehouse/#3-what-is-a-data-warehouse) : This link provides an overview of what a data warehouse is, its components, and its role in data management and business intelligence.

## Topics

![](topics/Concept/Sink%20Overwritability)