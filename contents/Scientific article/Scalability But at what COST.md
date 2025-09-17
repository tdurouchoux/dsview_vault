---
already_read: true
link: https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf
read_priority: 0
relevance: 5
source: null
tags:
- Data_Analysis
- Development_tool
type: Content
upload_date: '2025-02-11'
---

https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf
## Summary

The paper introduces a new metric called COST (Configuration that Outperforms a Single Thread) to evaluate the performance of big data platforms. COST measures the hardware configuration required for a platform to outperform a single-threaded implementation, providing a more accurate assessment of a system's scalability and performance gains.

The authors argue that many big data systems focus on scalability but often fail to outperform single-threaded implementations, even when using hundreds of cores. They present a methodology to compare recent graph processing systems against simple, single-threaded implementations on the same datasets, finding that many systems have unbounded COST or underperform single-threaded implementations.

The paper discusses two basic graph computations: PageRank and connected components. It shows that single-threaded implementations can outperform distributed systems, especially when using optimized graph layouts and better algorithms. The authors also apply the COST metric to prior work, finding that some systems have high COST due to intrinsic design choices or avoidable inefficiencies.

The paper concludes with lessons learned and future directions for the area, emphasizing the importance of evaluating COST to understand and articulate progress in scalable systems research. It highlights the need for better baselines, more efficient algorithms, and a focus on qualitative advantages that simpler solutions cannot provide. The authors encourage researchers to learn from past mistakes and focus on making meaningful progress in the field.
## Links


## Topics

![](topics/Concept/COST)

![](topics/Concept/Graph%20Processing)

![](topics/Concept/PageRank)

![](topics/Concept/Label%20Propagation)

![](topics/Concept/Union%20Find)

![](topics/Concept/Hilbert%20Curve)