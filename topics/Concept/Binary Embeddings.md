---
type: Concept
---

Binary embeddings are a type of embedding where the vector representations are binary (0 or 1) rather than continuous values. This approach allows for faster computations and lower memory usage, making it suitable for tasks that require high-speed processing. Binary embeddings are particularly useful in tasks like fuzzy deduplication and clustering, where the ability to quickly compare and group similar texts is crucial. They are often trained using techniques like the straight-through estimator, which enables the use of small integer arrays for even faster Hamming distance calculations.