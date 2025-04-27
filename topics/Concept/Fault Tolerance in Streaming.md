---
date: '2025-04-02'
type: Concept
---

Fault tolerance refers to the systems and methods in place that allow a streaming application to recover from failures without losing data or processing progress. In Spark Structured Streaming, this is achieved through the use of checkpointing, which saves the state of the application periodically, enabling it to recover and continue processing from the last consistent state after a failure.