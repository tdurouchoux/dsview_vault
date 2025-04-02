---
already_read: false
link: https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html
read_priority: 4
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2025-04-02'
---

https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html
## Summary

Structured Streaming in Spark 3.5.5 is a scalable and fault-tolerant stream processing engine that allows users to express streaming computations similarly to batch computations. It supports various programming languages (Scala, Java, Python, R) and provides a unified API for handling streaming data.

Key components include:

- **Programming Model**: Treats live data streams as continuously appended tables, allowing for incremental queries.
- **Event-time Handling**: Supports event-time processing and late data handling through watermarking, which helps manage state size.
- **Fault Tolerance**: Ensures exactly-once processing semantics using checkpointing and write-ahead logs.
- **DataFrames/Datasets**: Users can create streaming DataFrames from various sources (e.g., Kafka, socket, files) and perform operations like selection, aggregation, and windowing.
- **Join Operations**: Supports stream-static and stream-stream joins with specific requirements for watermarking and event-time constraints.
- **Output Modes**: Offers three output modes: Append, Complete, and Update, each with specific use cases.
- **Sinks**: Supports various output sinks, including file, Kafka, console, and memory sinks.
- **Triggers**: Allows users to define how often the query should process data (e.g., fixed intervals, continuous processing).
- **Monitoring and Management**: Users can manage and monitor queries using the StreamingQuery object and can report metrics using Dropwizard or custom listeners.

The guide also covers advanced topics like stateful operations, asynchronous progress tracking, and continuous processing mode for low-latency applications. It emphasizes the importance of checkpointing for recovery and provides examples for common use cases.
## Links

1. [Structured Network Word Count (Python)](https://github.com/apache/spark/blob/v3.5.5/examples/src/main/python/sql/streaming/structured_network_wordcount.py) - Example of a streaming word count application using Python in Spark.
2. [Structured Network Word Count (Java)](https://github.com/apache/spark/blob/v3.5.5/examples/src/main/java/org/apache/spark/examples/sql/streaming/JavaStructuredNetworkWordCount.java) - Example of a streaming word count application using Java in Spark.
3. [Real-time Streaming ETL with Structured Streaming](https://databricks.com/blog/2017/01/19/real-time-streaming-etl-structured-streaming-apache-spark-2-1.html) - Blog post discussing real-time streaming ETL using Spark's Structured Streaming.
4. [Event-time Aggregation and Watermarking in Apache Spark’s Structured Streaming](https://databricks.com/blog/2017/05/08/event-time-aggregation-watermarking-apache-sparks-structured-streaming.html) - Blog post explaining event-time aggregation and watermarking in Spark Structured Streaming.
5. [Deep Dive into Stateful Stream Processing in Structured Streaming](https://databricks.com/session/deep-dive-into-stateful-stream-processing-in-structured-streaming) - Session discussing stateful stream processing in Spark's Structured Streaming.
## Topics

![](topics/Concept/Structured%20Streaming)

![](topics/Concept/Micro%20batch%20Processing)

![](topics/Concept/Continuous%20Processing)

![](topics/Tool/Spark%20SQL)

![](topics/Tool/RocksDB)