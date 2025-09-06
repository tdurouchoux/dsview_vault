---
already_read: false
link: https://samwho.dev/reservoir-sampling/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Data_Analysis
type: Content
upload_date: '2025-05-14'
---

https://samwho.dev/reservoir-sampling/
## Summary

Reservoir sampling is a technique for selecting a fair random sample when the size of the set is unknown. Key points include:

- **Basic Concept**: When the size of the set is known, random sampling is straightforward. However, when the size is unknown, like in a streaming scenario, reservoir sampling provides a solution.
- **Problem Scenario**: Useful in scenarios like log collection services where the number of incoming logs is unpredictable and can overwhelm the system.
- **Algorithm**:
  - For selecting one item, each new item has a 1/n chance of being selected, where n is the number of items seen so far.
  - For selecting multiple items, each new item has a k/n chance of being selected, where k is the number of items to choose.
  - The algorithm ensures fairness by giving each item an equal chance of being selected.
- **Implementation**: Can be implemented using an array of size k, replacing elements based on random number generation.
- **Application**: In log collection, reservoir sampling can be used to send a fair sample of logs without overwhelming the system, ensuring predictable memory usage.
- **Extensions**: Weighted variants of reservoir sampling exist for scenarios where some items are more valuable than others.

The technique is elegant and efficient, solving a problem that initially seems impossible.
## Links

- [Weighted Random Sampling](https://en.wikipedia.org/wiki/Reservoir_sampling#Weighted_random_sampling) : Wikipedia article on weighted random sampling, a variant of reservoir sampling that allows for some elements to be more likely to be selected than others.

## Topics

![](topics/Concept/Reservoir%20Sampling)