---
type: Concept
---

Cache-friendly data structures are designed to optimize the use of CPU caches by minimizing cache misses. This can be achieved by ensuring that data is accessed in a sequential manner, which allows the CPU to pre-load data into the cache more effectively. In contrast, random access patterns can lead to cache misses, as the CPU cannot predict which data will be needed next. In Python, the use of pointers to more complex data structures, such as PyObject, can make data structures less cache-friendly compared to languages like C++ or Rust.