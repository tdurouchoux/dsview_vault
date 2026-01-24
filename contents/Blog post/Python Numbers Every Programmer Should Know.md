---
already_read: false
link: https://mkennedy.codes/posts/python-numbers-every-programmer-should-know/
read_priority: 2
relevance: 0
source: Data Elixir
tags:
- Python
type: Content
upload_date: '2026-01-24'
---

https://mkennedy.codes/posts/python-numbers-every-programmer-should-know/
## Summary

The content provides a comprehensive overview of performance metrics and memory usage for various Python operations, data structures, and libraries. It is structured into several categories, each highlighting key performance numbers and memory costs.

**Memory Costs:**
- An empty Python process uses 15.77 MB.
- Strings: Empty string is 41 bytes, with each additional character adding 1 byte.
- Numbers: Small integers (-5 to 256) and large integers use 28 bytes, while floats use 24 bytes.
- Collections: Empty list is 56 bytes, empty dict is 64 bytes, and empty set is 216 bytes.
- Classes and Instances: Regular class instances are larger (694 bytes for 5 attributes) compared to __slots__ class instances (212 bytes for 5 attributes).

**Basic Operations:**
- Arithmetic operations (add, multiply) on integers and floats are very fast, around 18-19 ns.
- String operations: Concatenation is fastest (~39 ns), followed by f-strings (~65 ns).
- List operations: Appending an item is ~29 ns, and list comprehensions are faster than equivalent for-loops.

**Collection Access and Iteration:**
- Dictionary and set lookups are extremely fast (~20 ns), while list membership checks are slower (~3.85 μs for 1,000 items).
- Iterating over a 1,000-item list or dict takes around 7.87-8.74 μs.

**Class and Object Attributes:**
- Reading and writing attributes is very fast (~14-16 ns), with minimal difference between regular and __slots__ classes.

**JSON and Serialization:**
- Alternative libraries like orjson and msgspec are significantly faster than the standard library json for both serialization and deserialization.

**Web Frameworks:**
- FastAPI and Starlette are the fastest frameworks for returning JSON responses, with latencies around 8-9 μs.

**File I/O:**
- Opening and closing a file takes ~9.1 μs, while writing a 1MB file takes ~207 μs.

**Database and Persistence:**
- SQLite operations (insert, select, update) are generally faster than MongoDB operations, with select by primary key being particularly fast (~3.6 μs).

**Function and Call Overhead:**
- Empty function calls are ~22 ns, and method calls are slightly slower (~23 ns).
- Exception handling has significant overhead, especially when an exception is raised (~140 ns).

**Async Overhead:**
- Creating and running coroutines has measurable overhead (~27-47 ns), and asyncio operations like sleep and gather have varying latencies.

**Key Takeaways:**
- Python objects have significant memory overhead.
- Dictionary and set lookups are extremely fast compared to list membership checks.
- Alternative JSON libraries offer better performance.
- Async operations have measurable overhead and should be used judiciously.
- __slots__ can save memory with minimal performance impact.
## Links

- [Python Numbers Everyone Should Know - Source Code](https://github.com/mikeckennedy/python-numbers-everyone-should-know) : Source code repository for the benchmarks and performance numbers discussed in the article.
- [Python Numbers Everyone Should Know - Detailed Results](https://github.com/mikeckennedy/python-numbers-everyone-should-know/blob/main/code/basic_ops/vs_dotnet/RESULTS.md) : Detailed results and comparisons of Python performance benchmarks against other technologies.

## Topics

![[topics/Library/orjson]]

![[topics/Library/msgspec]]

![[topics/Library/ujson]]

![[topics/Library/diskcache]]

![[topics/Library/Flask]]

![[topics/Library/Django]]

![[topics/Library/Litestar]]

![[topics/Library/Pydantic]]

![[topics/Library/FastAPI]]

![[topics/Library/Starlette]]