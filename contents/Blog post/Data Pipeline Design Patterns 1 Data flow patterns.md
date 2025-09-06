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

The content discusses data pipeline design patterns, focusing on data flow patterns. It begins by emphasizing the importance of solid data pipeline design to prevent flakiness over time. The post is structured into several sections:

1. **Introduction**: Highlights the need for understanding data pipeline design patterns and their pros, cons, and appropriate use cases.

2. **Source & Sink**: Explains the concepts of source (input systems) and sink (output systems) in data pipelines. It delves into:
   - **Source Replayability**: The ability of a source system to provide historical data.
   - **Source Ordering**: The order in which data is pulled from a source system.
   - **Sink Overwritability**: The ability of a sink system to update specific rows of existing data.

3. **Data Pipeline Patterns**: Covers three main categories of data pipeline patterns:
   - **Extraction Patterns**: Methods for pulling data from a source, including time-ranged, full snapshot, lookback, and streaming.
   - **Behavioral Patterns**: How data pipelines behave in case of failures and reruns, focusing on idempotent and self-healing pipelines.
   - **Structural Patterns**: How tasks/transformations are structured in a data pipeline, including multi-hop pipelines, conditional/dynamic pipelines, and disconnected data pipelines.

4. **Conclusion**: Summarizes the typical design patterns for organizing data flows through pipelines and emphasizes the importance of choosing the simplest design for new or refactored pipelines.

5. **Further Reading and References**: Provides additional resources and references for further learning.

The content aims to help data engineers and scientists understand and implement effective data pipeline design patterns.
## Links

- [Apache Flink Documentation on Event Time and Watermarks](https://nightlies.apache.org/flink/flink-docs-master/docs/concepts/time/#event-time-and-watermarks) : This link points to the Apache Flink documentation on event time and watermarks, which is relevant for understanding how to handle out-of-order events in streaming data pipelines.
- [DBT Documentation on Project Structure](https://docs.getdbt.com/docs/build/projects) : This link points to the DBT documentation on project structure, which is relevant for understanding how to structure data transformation projects using DBT.
- [Databricks Documentation](https://docs.databricks.com/) : This link points to the Databricks documentation, which is relevant for understanding the medallion architecture and other data engineering concepts discussed in the content.
- [Ecotrust Canada Markdown TOC Generator](http://ecotrust-canada.github.io/markdown-toc/) : This link points to the Ecotrust Canada Markdown TOC Generator, which is relevant for generating table of contents in markdown, a tool that might be useful for documentation.
- [Microsoft Documentation on Implementing Retries with Exponential Backoff](https://learn.microsoft.com/en-us/dotnet/architecture/microservices/implement-resilient-applications/implement-retries-exponential-backoff) : This link points to the Microsoft documentation on implementing retries with exponential backoff, which is relevant for understanding how to handle failures and retries in data pipelines.

## Topics

![](topics/Concept/Data%20Pipeline%20Design%20Patterns)

![](topics/Concept/Source%20Replayability)

![](topics/Concept/Source%20Ordering)

![](topics/Concept/Sink%20Overwritability)

![](topics/Concept/Extraction%20Patterns)

![](topics/Concept/Behavioral%20Patterns)

![](topics/Concept/Structural%20Patterns)