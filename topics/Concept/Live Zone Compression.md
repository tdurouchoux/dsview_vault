---
type: Concept
---

Live-zone compression is a dynamic compression method that focuses on compressing only the new or changing portions of the input data (e.g., fresh tool outputs or the latest conversation turn). The static or previously compressed segments remain unchanged, ensuring that provider-side KV caches (used by LLMs) are not invalidated. This approach optimizes both compression efficiency and cache utilization.