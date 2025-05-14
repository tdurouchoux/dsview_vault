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

Reservoir sampling is a method used for selecting random samples from a data stream when the total size of the dataset is unknown. Key points covered include:

- **Need for Reservoir Sampling**: Traditional sampling methods work well with known dataset sizes, but reservoir sampling is necessary when dealing with unknown sizes, such as continuous log streams.

- **Mechanics**: Instead of using coin flips to decide whether to keep or discard samples, each new sample is given a 1/n chance of being selected, where n is the number of samples seen so far. This ensures that all samples have an equal chance of being chosen.

- **Selection of Multiple Samples**: Reservoir sampling can be extended to select multiple items (k items) by adjusting the probabilities accordingly, ensuring fairness in selection.

- **Implementation for Log Collection**: This technique can be efficiently implemented in log collection systems to handle spikes in log messages while keeping memory usage predictable (holding only k logs).

- **Weighted Variants**: For scenarios where different log types (e.g., error logs) have varying importance, a weighted variant of reservoir sampling exists.

Reservoir sampling is valued for its efficiency and elegance, making it suitable for real-time data processing tasks.
## Links

- [Weighted Random Sampling - Wikipedia](https://en.wikipedia.org/wiki/Reservoir_sampling#Weighted_random_sampling) : A detailed explanation of weighted reservoir sampling, which selects samples based on their weights, allowing for prioritization of certain items.

## Topics

![](topics/Concept/Reservoir%20Sampling)

![](topics/Concept/Log%20Collection%20Services)

![](topics/Concept/Randomized%20Algorithms)

![](topics/Concept/Weighted%20Reservoir%20Sampling)