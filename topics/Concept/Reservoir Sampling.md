---
type: Concept
---

Reservoir sampling is a technique for selecting a fair random sample from a data stream of unknown size. It ensures that each element in the stream has an equal probability of being selected, making it useful for scenarios where the total number of elements is not known in advance. The algorithm works by maintaining a reservoir of a fixed size and updating it as new elements are encountered, using a probabilistic approach to decide whether to include new elements in the reservoir. This method is particularly valuable in log collection, data streaming, and other applications where memory efficiency and fairness in sampling are critical.