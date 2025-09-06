---
type: Concept
---

Cache / lru_cache in Python are decorators provided by the `functools` module that help optimize the performance of functions by caching their results. The `@cache` decorator, introduced in Python 3.9, caches the results of function calls, while the `@lru_cache` decorator, available since Python 3.2, caches the results of the last `maxsize` calls. These decorators are particularly useful for functions that are called frequently with the same arguments, as they can significantly reduce the computational overhead by avoiding redundant calculations.