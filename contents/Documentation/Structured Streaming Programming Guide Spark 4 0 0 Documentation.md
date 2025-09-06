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

The Structured Streaming Programming Guide for Spark 4.0.0 has been reorganized into smaller, more digestible sections. Key aspects include:

- **Overview**: Structured Streaming is a scalable, fault-tolerant stream processing engine built on Spark SQL.
- **Programming Model**: Uses the same DataFrame/Dataset API as batch processing, with streaming sources and sinks.
- **Key Concepts**:
  - **Micro-batch Processing**: Processes data in small batches.
  - **Event-Time Processing**: Handles out-of-order data.
  - **Watermarking**: Defines a threshold for late data.
  - **Output Modes**: Append, Update, and Complete modes for writing output.
- **Sources and Sinks**: Supports various streaming sources (e.g., Kafka, files) and sinks (e.g., Kafka, files, databases).
- **Fault Tolerance**: Ensures exactly-once processing guarantees.
- **Performance Tuning**: Tips for optimizing streaming jobs.
- **Integration**: Works with Spark SQL, DataFrames, and Datasets.

The guide is now split into smaller pages for easier navigation and understanding.
## Links

- [Contributing to Spark](https://spark.apache.org/contributing.html) : This link provides information on how to contribute to the Apache Spark project, including guidelines and processes for contributing code, documentation, and other resources.
- [Third Party Projects](https://spark.apache.org/third-party-projects.html) : This link lists third-party projects that are built on top of or integrate with Apache Spark, providing additional tools and resources for Spark users.

## Topics

![](topics/Concept/Structured%20Streaming)