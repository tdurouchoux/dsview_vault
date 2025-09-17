---
type: Concept
---

Near real-time (NRT) features are precomputed using streaming processing engines like Flink or Spark Streaming. They offer fresh features with low staleness, typically in the order of seconds, and avoid wasted computation by recomputing features only when necessary. NRT features are suitable for use cases requiring up-to-date data without the latency of real-time computation.