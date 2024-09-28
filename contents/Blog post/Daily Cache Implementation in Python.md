---
already_read: true
link: https://maxhalford.github.io/blog/python-daily-cache/?ref=blef.fr
read_priority: 0
source: Data Elixir
tags:
- Python
- Data_Engineering
type: Content
upload_date: '2024-09-28'
---

https://maxhalford.github.io/blog/python-daily-cache/?ref=blef.fr
## Summary

Max Halford discusses the implementation of a caching mechanism in Python to optimize data loading from customer datasets. He initially uses `functools.cache`, which stores outputs in RAM but loses the cache upon restarting the computer or reloading a Jupyter notebook. To address this, he employs the `joblib` library to create a persistent cache on disk.

Halford introduces a custom cache validation callback to ensure the cache is refreshed daily, allowing the function to re-fetch data if it hasn't been updated since the last call. He demonstrates unit testing for the caching decorator using the `FreezeGun` package to simulate different timestamps.

While the solution works well, he notes a potential issue: if customers update their data on the same day, the cache may still hit, leading to processing outdated information. He suggests that an ideal caching mechanism would check the last modification date of the remote files, which can be complex due to varying cloud storage solutions. He mentions `fsspec`, a package that provides a unified interface for different file systems, as a promising approach for handling this challenge.
## Links

1. [functools documentation](https://docs.python.org/3/library/functools.html) - Official Python documentation for the functools module, which includes the cache decorator used in the source.
2. [Joblib Memory documentation](https://joblib.readthedocs.io/en/latest/memory.html#memory) - Documentation for the Joblib library's memory caching functionality, relevant for persisting cache to disk.
3. [Joblib Custom Cache Validation](https://joblib.readthedocs.io/en/latest/memory.html#custom-cache-validation) - Details on how to implement custom cache validation in Joblib, which is crucial for the daily cache mechanism discussed.
4. [FreezeGun GitHub repository](https://github.com/spulec/freezegun) - A library for freezing time in tests, useful for unit testing the caching mechanism.
5. [Filesystem Spec documentation](https://filesystem-spec.readthedocs.io/en/latest/index.html) - Documentation for fsspec, a library that provides a common interface to various file systems, including cloud storage solutions.
## Topics

- [[topics/Library/joblib]]
- [[topics/Library/functools]]
- [[topics/Library/freezegun]]
- [[topics/Concept/daily cache validation]]
- [[topics/Library/fsspec]]