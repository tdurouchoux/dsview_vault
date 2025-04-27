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

The paper presents a new metric, COST (Configuration that Outperforms a Single Thread), to evaluate big data platforms based on hardware requirements needed for these systems to outperform effective single-threaded implementations. This metric highlights the trade-offs between scalability and overheads, revealing systems that may appear scalable but introduce significant performance penalties due to parallelizable overheads.

Key findings include that many data-parallel systems possess high COST or fail to surpass single-threaded implementations, even when using numerous cores. The authors conducted a methodology comparing various graph-processing systems' performance against single-threaded counterparts using a standard high-end laptop from 2014.

The paper discusses specific algorithms like PageRank and label propagation, demonstrating that single-threaded implementations often outperform distributed systems significantly, with some systems showing performance gaps of over an order of magnitude. The authors emphasize the importance of better baselines and argue for improvements by adopting efficient algorithms and optimal data layouts, ultimately aiming to foster better design standards in scalable systems.

The paper concludes that high COST may not solely reflect poor system design but also differing problem targets or experimental prototypes. The authors recommend further research in scalable systems while providing a framework for assessing progress in distributed computing.
## Topics

![](topics/Concept/Scalability)

![](topics/Concept/Performance%20Metrics)

![](topics/Model/PageRank)

![](topics/Concept/Graph%20Processing)

![](topics/Platform/GraphLab)

![](topics/Platform/GraphX)

![](topics/Concept/Label%20Propagation)

![](topics/Concept/Union%20Find%20Algorithm)