---
already_read: true
link: https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf
read_priority: 0
relevance: 5
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2025-02-11'
---

![](artefacts/hotos15-paper-mcsherry.pdf)
## Summary

The paper introduces a new metric called COST (Configuration that Outperforms a Single Thread) to evaluate big data platforms, focusing on the hardware configuration needed for a system to outperform a single-threaded implementation. The authors argue that many systems exhibit high COST, indicating that they may not provide significant performance improvements over simpler implementations, often due to overheads introduced by parallelization.

Key points include:

- The emphasis on scalability in big data systems often overshadows the need for absolute performance evaluation against benchmarks.
- Many published systems have unbounded COST, meaning they do not outperform single-threaded implementations even when using hundreds of cores.
- The authors conducted comparisons of various graph processing systems against single-threaded implementations, revealing that single-threaded versions often outperform distributed systems significantly.
- They highlight the importance of algorithm choice and data layout in achieving better performance, suggesting that many systems use suboptimal algorithms that do not leverage the full potential of parallelism.
- The paper calls for a reevaluation of how performance is measured in distributed systems, advocating for a focus on systems that achieve scalability through effective design rather than through inflated performance claims.

The authors conclude that understanding the COST of a system is crucial for identifying inefficiencies and guiding future research towards more effective scalable systems. They also suggest that there is still valuable work to be done in improving scalable algorithms and computational models.
## Topics

![](topics/Concept/COST)

![](topics/Concept/Scalability)

![](topics/Concept/Graph%20Processing)