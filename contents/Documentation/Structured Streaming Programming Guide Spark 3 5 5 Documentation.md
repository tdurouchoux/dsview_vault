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

Structured Streaming in Spark 3.5.5 is designed for scalable, fault-tolerant stream processing, allowing for both batch-like queries on streaming data. Key concepts include:

- **Programming Model**: Treats a streaming data source as a continuously appended table. Queries generate result tables that update incrementally.
  
- **Output Modes**: 
  - **Append**: Outputs only new rows.
  - **Complete**: Outputs the entire result table.
  - **Update**: Outputs only changed rows since the last trigger.

- **Event-Time Handling**: Supports event-time windowing, ensuring accurate aggregations on late-arriving data through watermarking. Users can define late thresholds to manage state size.

- **Join Operations**: 
  - **Stream-Static Joins**: Supports inner and left outer joins with static DataFrames.
  - **Stream-Stream Joins**: Allow inner joins with watermarking to manage state. Outer joins require event-time constraints.

- **State Management**: Supports arbitrary stateful operations, with state stored in either in-memory or using RocksDB. It provides mechanisms for deduplication and sessionization.

- **Fault Tolerance**: Achieved via checkpointing and write-ahead logs, allowing queries to resume from their last checkpoint.

- **Starting Queries**: Utilizes `writeStream` to define sinks (e.g., files, Kafka, console), requiring a checkpoint location for fault tolerance.

- **Monitoring**: Use StreamingQuery objects to track query progress, and connect a custom listener for event handling.

- **Asynchronous Progress Tracking**: Improves latency by checkpointing progress independently from data processing.

- **Continuous Processing (Experimental)**: Introduces low-latency processing (as low as 1 ms) with at-least-once guarantees.

In summary, Spark Structured Streaming provides a robust framework for processing continuous data streams with capabilities for real-time analytics, simplified event-time handling, and flexible state management, facilitating a wide range of applications.
## Links

- [Real-time Streaming ETL with Structured Streaming in Apache Spark 2.1](https://databricks.com/blog/2017/01/19/real-time-streaming-etl-structured-streaming-apache-spark-2-1.html) : An article discussing the capabilities of Structured Streaming for efficient real-time ETL processes.
- [Event-time Aggregation and Watermarking in Apache Spark’s Structured Streaming](https://databricks.com/blog/2017/05/08/event-time-aggregation-watermarking-apache-sparks-structured-streaming.html) : A blog post explaining the concepts of event-time aggregation and watermarking in Structured Streaming.
- [Deep Dive into Stateful Stream Processing in Structured Streaming](https://databricks.com/session/deep-dive-into-stateful-stream-processing-in-structured-streaming) : A presentation covering advanced stateful stream processing capabilities in Apache Spark's Structured Streaming.
- [Kafka Integration with Structured Streaming](https://databricks.com/blog/2017/04/04/real-time-end-to-end-integration-with-apache-kafka-in-apache-sparks-structured-streaming.html) : This blog details how to integrate Apache Kafka with Spark's Structured Streaming.
- [Spark Summit 2016 - A Deep Dive into Structured Streaming](https://spark-summit.org/2016/events/a-deep-dive-into-structured-streaming/) : Slides and video from a talk at the Spark Summit 2016 regarding the features of Structured Streaming.

## Topics

![](topics/Concept/Streaming%20DataFrames)

![](topics/Concept/Fault%20Tolerance%20in%20Streaming)

![](topics/Library/Apache%20Spark)

![](topics/Concept/Watermarking%20in%20Streams)

![](topics/Concept/Windowing%20in%20Stream%20Processing)

![](topics/Concept/Micro%20Batch%20Processing)

![](topics/Tool/Kafka)

![](topics/Concept/Continuous%20Processing%20Mode)

![](topics/Concept/Stateful%20Operations%20in%20Streams)

![](topics/Tool/RocksDB)