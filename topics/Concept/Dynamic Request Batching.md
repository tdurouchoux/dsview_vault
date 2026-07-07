---
type: Concept
---

Dynamic request batching is a performance optimization technique used in model serving to group multiple inference requests into a single batch. This approach improves throughput, especially for GPU-based models, by leveraging vectorized operations. Ray Serve supports dynamic request batching to enhance efficiency and reduce latency in serving large-scale applications.