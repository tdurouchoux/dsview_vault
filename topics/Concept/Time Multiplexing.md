---
type: Concept
---

Time-multiplexing is a technique used in hardware design to reuse a single resource (e.g., a computational unit) for multiple tasks over time. In Talos V2, a single reusable matrix-vector multiplication tile is time-multiplexed across different layers of the transformer model. This approach optimizes area and resource usage by reducing the need for separate datapaths for each layer, while still maintaining sufficient throughput for the application.