---
type: Concept
---

Sink Overwritability refers to the ability of a data storage system to update specific rows of existing data. This is crucial for preventing duplicates or partial records when a pipeline fails. Overwritable sinks include database tables with unique keys and cloud storage systems namespaced by unique run IDs, while non-overwritable sinks include Kafka queues without log compaction and databases without unique keys.