---
type: Concept
---

Sink Overwritability refers to the ability of a data sink to update specific rows of existing data. This is crucial for preventing duplicates or partial records when a pipeline fails. Overwritable sinks include database tables with unique keys and cloud storage systems namespaced by unique run IDs. Non-overwritable sinks, such as Kafka queues without log compaction, do not support updating specific rows, which can lead to data inconsistencies if not managed properly.