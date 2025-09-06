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

The paper introduces a new metric called COST (Configuration that Outperforms a Single Thread) to evaluate the performance of big data platforms. COST measures the hardware configuration required for a platform to outperform a single-threaded implementation, highlighting the actual performance gains and accounting for system overheads.

Key points include:

1. **Introduction of COST Metric**: COST is proposed to assess the scalability and efficiency of big data systems by comparing their performance against a competent single-threaded implementation.

2. **Survey Findings**: Many data-parallel systems have high COST values, often requiring hundreds of cores to outperform a single thread, or they fail to outperform a single thread at all.

3. **Methodology**: The paper compares recent graph processing systems against single-threaded implementations on the same datasets, revealing significant performance gaps.

4. **Graph Computations**: The paper evaluates systems on tasks like PageRank and connected components, showing that single-threaded implementations often outperform distributed systems, sometimes by an order of magnitude.

5. **Improving Baselines**: The paper suggests improvements to single-threaded implementations, such as better graph layout (e.g., Hilbert curve ordering) and more efficient algorithms (e.g., Union-Find), which can further enhance performance.

6. **Applying COST**: The paper applies the COST metric to existing systems like PowerGraph, GraphX, and Naiad, finding that some systems have high or unbounded COST, indicating inefficiencies.

7. **Lessons Learned**: The paper discusses factors contributing to high COST, including restrictive computational models, hardware trade-offs, and implementation overheads. It emphasizes the importance of evaluating COST to identify and address inefficiencies.

8. **Future Directions**: The paper encourages further research to understand and improve scalable systems, learn from past mistakes, and focus on meaningful progress in distributed systems research.

The paper aims to promote a more rigorous evaluation of big data systems, ensuring that scalability claims are backed by actual performance improvements.
## Links


## Topics

![](topics/Concept/COST)

![](topics/Concept/Graph%20Processing)

![](topics/Concept/PageRank)

![](topics/Concept/Label%20Propagation)

![](topics/Concept/Union%20Find)

![](topics/Concept/Hilbert%20Curve)