---
type: Concept
---

Reservoir sampling is a technique for selecting a fair random sample when the size of the set being sampled from is unknown. It ensures that each element in the stream has an equal probability of being included in the final sample. This method is particularly useful in scenarios where the total number of elements is not known in advance, such as in log collection services or streaming data applications. The algorithm works by maintaining a reservoir of elements and updating it as new elements are encountered, using a probabilistic approach to decide whether to include new elements in the reservoir.