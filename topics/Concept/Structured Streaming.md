---
type: Concept
---

Structured Streaming is a scalable and fault-tolerant stream processing system that is built on the Spark SQL engine. It allows for processing of streaming data in a structured way, similar to how batch processing is done on static data. This enables developers to apply batch processing code to streaming data seamlessly, making it easier to work with real-time data streams. Structured Streaming provides end-to-end exactly-once processing guarantees, which ensures that each record is processed exactly once, even in the event of failures. It supports a wide range of data sources and sinks, including Kafka, files, sockets, and databases, making it versatile for various use cases.