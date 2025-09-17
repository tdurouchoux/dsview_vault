---
type: Concept
---

Cache and lru_cache in Python are decorators from the functools module that provide memoization capabilities. The @cache decorator, introduced in Python 3.9, caches function results to speed up recursive functions and expensive calculations. The @lru_cache decorator, introduced in Python 3.2, offers similar functionality with explicit control over cache size. These decorators help optimize performance by avoiding redundant computations.