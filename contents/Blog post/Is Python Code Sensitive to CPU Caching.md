---
already_read: false
link: https://lukasatkinson.de/2024/python-cpu-caching/
read_priority: 5
relevance: 0
source: ArjanCodes
tags:
- Python
type: Content
upload_date: '2025-05-26'
---

https://lukasatkinson.de/2024/python-cpu-caching/
## Summary

The blog post explores whether Python code is sensitive to CPU caching effects by conducting experiments comparing linear vs. random access of list elements. Key findings include:

- Cache-aware programming enhances performance significantly in lower-level languages like C++, but Python, being high-level, lacks direct memory layout control.
- Experiments reveal that random access remains slower than sequential access, especially as data sizes exceed CPU cache sizes; performance gaps increase from 23% to 280% slower for random access as data grows.
- The author designs an experiment to validate that access patterns affect execution time, utilizing Python's structure for memory layout and analyzing how data type overhead influences performance.
- Results indicate that for small datasets (sizes under 200,000), random and linear accesses perform similarly. However, as the problem size increases, linear access consistently outperforms scrambled access.
- The bonus section addresses indirection overhead from Python's data structures, demonstrating that using NumPy drastically improves performance due to lower memory overhead.

The conclusion emphasizes that while caching effects can impact performance in Python, the practical significance may be limited since CPU-bound Python operations on large lists (>10,000 elements) are not common. Recommendations for further reading include insights into CPU microarchitecture and resource optimization techniques.
## Links

- [Napkin Math Collection](https://github.com/sirupsen/napkin-math) : A collection of tables and useful resources focused on performance-related metrics and factors.
- [Hyperfine Benchmarking Tool](https://github.com/sharkdp/hyperfine) : A command-line benchmarking tool that allows for easy and accurate benchmarking of command line programs.
- [Agner Fog's Optimization Manuals](https://agner.org/optimize/) : Extensive resources on microarchitecture details and optimization techniques for various programming languages.
- [Norvig's 21 Days to Learn the U.N.](https://norvig.com/21-days.html#answers) : A collection of programming challenges to improve coding skills, including insights into performance-related issues.

## Topics

![](topics/Concept/Cache%20aware%20Programming)

![](topics/Concept/Performance%20Benchmarking)

![](topics/Tool/Hyperfine)

![](topics/Library/NumPy)