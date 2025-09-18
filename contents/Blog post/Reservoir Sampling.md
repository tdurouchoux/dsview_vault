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

Reservoir sampling is a technique for selecting a fair random sample when the size of the set is unknown. The essay explains the mathematics behind it using basic operations and provides a simple implementation method.

The post begins by discussing sampling when the size is known, using a deck of cards as an example. It then introduces the problem of sampling when the size is unknown, such as in a log collection service that receives an unpredictable number of logs.

The solution presented is reservoir sampling, which ensures that each card (or log) has an equal chance of being selected. The algorithm works by giving each new card a 1/n chance of being selected, where n is the number of cards seen so far. This method can be extended to select multiple cards by adjusting the probability and randomly replacing a held card.

The essay concludes by applying reservoir sampling to the log collection service, demonstrating its effectiveness in handling log spikes while maintaining fairness. It also mentions a weighted variant of reservoir sampling for logs of varying importance and encourages further reading. The author expresses gratitude to the sponsor and readers for their feedback and support.
## Links

- [Reservoir Sampling - Wikipedia](https://en.wikipedia.org/wiki/Reservoir_sampling#Weighted_random_sampling) : Wikipedia page on Reservoir Sampling, including a section on Weighted Random Sampling.

## Topics

![[topics/Concept/Reservoir Sampling)]]