---
type: Concept
---

A mechanism in NumPy that resolves the appropriate data type and implementation for an operation based on input types. It involves selecting the correct loop (e.g., for float64 addition) and caching the result for future calls to avoid repeated resolution overhead.