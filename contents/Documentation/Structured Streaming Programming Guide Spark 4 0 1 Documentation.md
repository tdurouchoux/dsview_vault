---
already_read: false
link: https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html
read_priority: 4
relevance: 0
source: null
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2025-04-02'
---

https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html
## Summary

The Structured Streaming Programming Guide in Spark 4.0.1 has been reorganized into smaller, more digestible sections. Structured Streaming is a scalable and fault-tolerant stream processing engine built on the Spark SQL engine. Key features include:

- **Event-Time Processing**: Processes data based on the time the data was generated, not when it was received.
- **Stateful Operations**: Supports operations like aggregations, joins, and windowing over streaming data.
- **Fault Tolerance**: Ensures that data is processed exactly once, even in the presence of failures.
- **Integration with Spark SQL**: Allows the use of DataFrame and Dataset APIs for stream processing.
- **Output Modes**: Supports append, update, and complete output modes to control how results are written.

The guide covers the basics of setting up a streaming query, processing sources and sinks, and handling watermarking for late data. It also discusses performance tuning and monitoring for streaming applications. The content is structured to provide a comprehensive understanding of building and managing streaming applications using Spark's Structured Streaming.
## Links

- [Contributing to Spark](https://spark.apache.org/contributing.html) : This link provides information on how to contribute to the Apache Spark project, including guidelines for contributing code, documentation, and other resources.

## Topics

![](topics/Concept/Structured%20Streaming)