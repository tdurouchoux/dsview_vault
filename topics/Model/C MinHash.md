---
type: Model
---

C-MinHash is a practical variant of the MinHash algorithm that uses two seeded nonlinear permutations and 64-bit signature slots. It is designed for streaming deduplication, where it indexes candidate signatures and stops comparisons early if a pair cannot meet the similarity threshold.