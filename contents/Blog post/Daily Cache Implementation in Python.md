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

Halford introduces a custom cache validation callback to ensure the cache is refreshed daily, allowing the function to re-fetch data if it hasn't been updated since the last call. He demonstrates unit testing for the caching mechanism using the `FreezeGun` package to simulate different timestamps.

While the solution works well, he notes a limitation: if customers update their data on the same day, the cache may still hit, leading to potential errors. He suggests that an ideal caching system would check the last modification date of the remote files, which can be complex due to varying cloud storage solutions. He mentions `fsspec`, a package that provides a unified interface for different file systems, as a potential solution for managing file changes more effectively.
## Links

1. [Filesystem Spec Documentation](https://filesystem-spec.readthedocs.io/en/latest/features.html#caching-files-locally) - Provides information on local caching with fsspec, which is relevant for managing file caching across different storage solutions.
2. [Freezegun GitHub Repository](https://github.com/spulec/freezegun) - A library for mocking the current time in Python, useful for unit testing the caching mechanism described in the source.
3. [Joblib Memory Documentation](https://joblib.readthedocs.io/en/latest/memory.html#custom-cache-validation) - Details on how to implement custom cache validation in Joblib, which is central to the caching strategy discussed.
4. [Joblib Memory Overview](https://joblib.readthedocs.io/en/latest/memory.html#memory) - General information about Joblib's memory caching capabilities, relevant for understanding the caching implementation.
5. [functools Documentation](https://docs.python.org/3/library/functools.html) - Official Python documentation for functools, which includes details on the cache decorator used in the source.
## Topics

![](topics/Library/joblib)

![](topics/Library/functools)

![](topics/Library/freezegun)

![](topics/Library/fsspec)

![](topics/Concept/daily%20cache%20validation)