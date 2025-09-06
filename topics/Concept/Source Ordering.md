---
type: Concept
---

Source Ordering refers to the sequence in which data is pulled from a source system. Some data pipelines require data to be in a specific order, such as ensuring that a log-out event occurs after a log-in event. Techniques like exponential backoff, watermarking, and handling late events are used to manage out-of-order data. Proper source ordering is essential for maintaining data integrity and accuracy in the pipeline.