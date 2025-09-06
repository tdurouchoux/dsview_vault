---
already_read: false
link: https://lukasatkinson.de/2024/python-cpu-caching/
read_priority: 5
relevance: 0
source: ArjanCodes
tags:
- Python
- Data_Analysis
type: Content
upload_date: '2025-05-26'
---

https://lukasatkinson.de/2024/python-cpu-caching/
## Summary

The blog post by Lukas Atkinson explores whether Python code is sensitive to CPU caching effects, despite being a high-level language with less control over memory layout compared to languages like C++ or Rust. The author conducts experiments to compare sequential and random access to list elements in Python, using CPython 3.12 on an x86-64 architecture with a Zen 2 microarchitecture CPU.

Key findings include:

- Random access is consistently slower than sequential access in Python, especially when data sets exceed CPU cache sizes.
- For small data sets (below 200,000 elements), random access is about 24% slower.
- For large data sets (above 400,000 elements), random access can be up to 280% slower.
- Using NumPy arrays, which avoid Python's object overhead and pointer indirection, significantly improves performance and reduces cache effects.
- The experiments suggest that cache-aware programming can be relevant even in interpreted environments like Python.

The post concludes that while Python may be slower than native code, cache effects can still have a measurable impact on performance, particularly for CPU-bound code using large lists. The author provides further reading resources on microarchitecture details and performance optimization.
## Links

- [Agner Fog's optimization manuals](https://agner.org/optimize/) : Agner Fog's optimization manuals are an indispensable and fairly accessible resource on microarchitecture details. For example, the microarchitecture manual provides tables on cache latencies, and the C++ and assembly optimization manuals each contain sections on optimizing memory access patterns.
- [Sirupsen's Napkin Math collection](https://github.com/sirupsen/napkin-math) : Sirupsen's Napkin Math collection provides similar tables that are more up to date, but is focused more on general system performance. The collection to further performance resources is particularly nice.

## Topics

![](topics/Concept/CPU%20Caching)

![](topics/Concept/Cache%20aware%20programming)

![](topics/Concept/Cache%20effects)

![](topics/Concept/Cache%20friendly%20data%20structures)

![](topics/Concept/Interpreter%20overhead)

![](topics/Concept/Memory%20access%20patterns)

![](topics/Concept/Cache%20pressure)