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

The blog post explores whether Python code is sensitive to CPU caching effects, despite being a high-level language with less control over memory layout compared to languages like C++ or Rust. The author conducts experiments to compare sequential and random access patterns in Python lists, using CPython 3.12 on an x86-64 architecture with a Zen 2 microarchitecture CPU.

Key points include:

- **Background**: CPU caches are faster but smaller than RAM. The CPU pre-loads data based on access patterns. Sequential access is cache-friendly, while random access is not. Python objects are represented as pointers to more complex data structures, which may not be as cache-friendly as data structures in lower-level languages.
- **Experiment Design**: The author designs an experiment to compare the performance of sequential and random access to list elements. The experiment involves generating test data, parsing it, and running benchmarks using the hyperfine tool.
- **Results**:
  - **Small Data Sets**: For problem sizes below around 200,000, random access is consistently slower than sequential access, with a slowdown factor of around 1.24 to 1.47.
  - **Large Data Sets**: As problem sizes increase beyond the CPU cache size, the performance gap between sequential and random access widens significantly. For a problem size of 1.6 million elements, random access is about 3.8 times slower than sequential access.
  - **Bonus Round**: The author also compares the performance of vanilla Python with NumPy arrays. NumPy arrays, being more cache-friendly due to their dense packing and lack of pointer indirection, show a considerable performance advantage. However, when comparing memory usage, both implementations are affected by cache pressure, with the cache-friendly version being faster.

- **Conclusion**: The experiments demonstrate that CPU caching effects are measurable in Python code. Random access is significantly slower, especially as problem sizes increase. While the practical impact may be negligible for typical Python code, optimizing access patterns can be beneficial for CPU-bound Python code.

- **Further Reading**: The author suggests additional resources for understanding microarchitecture details, cache latencies, and performance optimization.
## Links

- [Hyperfine GitHub Repository](https://github.com/sharkdp/hyperfine) : The GitHub repository for Hyperfine, a command-line benchmarking tool used in the experiments to measure the performance of Python code with different access patterns.
- [Agner Fog's Optimization Manuals](https://agner.org/optimize/) : A collection of manuals by Agner Fog providing detailed information on microarchitecture details, cache latencies, and optimization techniques for C++ and assembly.
- [Norvig's Latencies Every Programmer Should Know](https://norvig.com/21-days.html#answers) : A resource by Peter Norvig that provides an overview of various latencies that every programmer should be aware of, including CPU cache effects and memory access times.
- [Sirupsen's Napkin Math Collection](https://github.com/sirupsen/napkin-math) : A collection of performance-related resources and tables by Sirupsen, focusing on system performance and providing up-to-date information on latencies and performance optimization.

## Topics

![[topics/Concept/Memory access patterns)]]

![[topics/Concept/Cache pressure)]]

![[topics/Concept/CPU Caching)]]

![[topics/Concept/Benchmarking)]]

![[topics/Concept/Cache aware programming)]]

![[topics/Concept/Cache friendly data structures)]]

![[topics/Concept/Interpreter overhead)]]