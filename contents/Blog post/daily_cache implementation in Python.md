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

The content discusses a custom Python decorator, `@daily_cache`, designed to cache data to disk and invalidate the cache daily. The author, Max Halford, works with large datasets that are updated once a day by customers. Initially, they use Python's built-in `@functools.cache`, which caches data in RAM but loses the cache upon computer restart or Jupyter notebook reload.

To persist the cache to disk, the author uses `joblib.Memory`. However, the default cache does not invalidate based on a daily schedule. The author creates a custom cache validation callback that checks if the last cache hit was on the same day, ensuring the cache is invalidated daily.

The solution is tested using the `FreezeGun` package to simulate different dates and times, demonstrating that the cache is invalidated correctly at the start of each new day.

The author acknowledges a limitation: if a customer fixes and re-uploads data on the same day, the cache will not reflect the changes, requiring manual cache clearing. An ideal solution would check the last modification date of the remote file, but this is complex due to varying cloud storage solutions. The author suggests `fsspec` as a potential solution for handling different file systems and implementing more intelligent caching based on file changes.
## Links

- [Joblib Memory Documentation](https://joblib.readthedocs.io/en/latest/memory.html#memory) : Documentation for the joblib.Memory class, which is used for caching data to disk.
- [Joblib Custom Cache Validation](https://joblib.readthedocs.io/en/latest/memory.html#custom-cache-validation) : Documentation on custom cache validation in joblib, allowing for custom cache invalidation logic.
- [Filesystem Spec Documentation](https://filesystem-spec.readthedocs.io/en/latest/index.html) : Documentation for the Filesystem Spec (fsspec) project, which provides a common interface to many file systems, including cloud storage solutions.
- [Freezegun GitHub Repository](https://github.com/spulec/freezegun) : GitHub repository for the Freezegun package, which is used for unit testing the @daily_cache decorator by freezing time.

## Topics

![](topics/Library/joblib)

![](topics/Library/functools)

![](topics/Library/FreezeGun)

![](topics/Library/fsspec)