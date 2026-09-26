---
type: Concept
---

A generalization of the completeness principle in streaming analytics, where systems declare constraints on what data can change, when, and in what order. This concept extends beyond time-based watermarks to include arbitrary predicates (e.g., account closure) and ordering constraints. It enables systems to provide stronger consistency guarantees and optimize processing by skipping re-verification of immutable data. Systems like Delta Live Tables and Snowflake Dynamic Tables leverage this concept to improve efficiency and correctness.