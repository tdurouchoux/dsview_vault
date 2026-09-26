---
type: Concept
---

A heuristic signal of event-time progress in streaming systems, used to estimate the completeness of data and trigger actions like emitting results or emitting retractions. Watermarks became a widely adopted mechanism in systems like Apache Flink, Spark, and Kafka Streams, enabling low-latency processing while providing a completeness estimate. They are particularly useful for use cases requiring single conclusive answers or reasoning about absence in data.