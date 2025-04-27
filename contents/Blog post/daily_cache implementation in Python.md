---
already_read: true
link: https://maxhalford.github.io/blog/python-daily-cache/
read_priority: 0
relevance: 0
source: Data Elixir
tags:
- Python
- Data_Engineering
type: Content
upload_date: '2024-09-28'
---

https://maxhalford.github.io/blog/python-daily-cache/
## Summary

The content discusses a Python implementation of a caching mechanism for loading customer data efficiently, particularly for scenarios involving heavy datasets processed daily. 

Key Points:

1. **Current Caching Limitations**: The author uses Python's `functools.cache` for caching data in RAM, but it resets upon restarting the computer or reloading Jupyter notebooks, which is inefficient for daily data that doesn't change throughout the day.

2. **Persistent Caching with `joblib`**: The solution involves using `joblib` to achieve persistent caching by storing cache data on disk. It also highlights the potential issue: caches do not invalidate on a daily basis but remain valid as long as data hasn't changed.

3. **Custom Cache Validation**: A custom validation callback is implemented to ensure that cached data is only fetched again once a day. This involves comparing the timestamp of the last cache hit with the current date.

4. **Testing with `FreezeGun`**: The author demonstrates how to unit test this caching mechanism with `freeze_time` from the `FreezeGun` package to simulate different dates and verify the cache behavior.

5. **Potential Issues**: The solution needs refinement as it may lead to using stale data if customers update their datasets within the same day. Ideally, a system should automatically check for file modifications, which poses challenges with diverse cloud storage systems.

6. **Future Considerations**: Introduction of `fsspec`, a package providing a unified interface for various file systems, is suggested to improve the caching mechanism but needs further exploration for handling modification checks reliably.

Overall, the implementation presents an efficient approach to caching with flexibility, though some shortcomings and areas for improvement are acknowledged.
## Links

- [functools documentation](https://docs.python.org/3/library/functools.html) : Official Python documentation for the functools module, which provides tools for higher-order functions and operations on callable objects.
- [joblib Memory documentation](https://joblib.readthedocs.io/en/latest/memory.html#memory) : Documentation for joblib's Memory class, which allows for efficient caching of data in Python.
- [joblib custom cache validation](https://joblib.readthedocs.io/en/latest/memory.html#custom-cache-validation) : Detail on how to implement custom cache validation in joblib's Memory, allowing for greater control over caching behavior.
- [fsspec documentation](https://filesystem-spec.readthedocs.io/en/latest/index.html) : Documentation for fsspec, a Python package that provides a unified interface for various file systems.
- [freezegun GitHub repository](https://github.com/spulec/freezegun) : GitHub repository for Freezegun, a Python library that allows you to easily mock the datetime module for testing.

## Topics

![](topics/Library/joblib)

![](topics/Concept/Caching)

![](topics/Library/functools)

![](topics/Library/freezegun)

![](topics/Platform/Filesystem%20Spec%20fsspec)