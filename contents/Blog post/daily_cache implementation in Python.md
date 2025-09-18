---
already_read: true
link: https://maxhalford.github.io/blog/python-daily-cache/
read_priority: 0
relevance: 0
source: Data Elixir
tags:
- Python
type: Content
upload_date: '2024-09-28'
---

https://maxhalford.github.io/blog/python-daily-cache/
## Summary

The content discusses a Python implementation for caching data with a daily invalidation mechanism. The author, Max Halford, describes a scenario where customer data is fetched and processed daily, and the need to cache this data to save time during development. The standard `functools.cache` is used initially, but it only caches in RAM, which is lost when the computer is turned off.

To persist the cache to disk, the author uses `joblib.Memory`, but notes that the cache is never invalidated. To address this, a custom cache validation callback is implemented to invalidate the cache daily. This is done by comparing the last call time stored in the cache metadata with the current date.

The implementation is tested using the `FreezeGun` package to simulate different dates and times. The author acknowledges that the solution is not perfect, as it does not account for cases where data is re-uploaded on the same day. The author suggests that an ideal solution would check the last modification date of the remote file, but this is complex due to the variety of cloud storage solutions used by customers.

Finally, the author mentions `fsspec` as a promising solution that provides a common interface to many file systems, including cloud storage, and could potentially be used to implement a more robust caching mechanism.
## Links

- [Python functools documentation](https://docs.python.org/3/library/functools.html) : Python's functools library documentation, which includes the @cache decorator used for caching function outputs in RAM.
- [Joblib Memory Documentation](https://joblib.readthedocs.io/en/latest/memory.html#memory) : Joblib's Memory documentation, explaining how to persist cache data to disk.
- [Joblib Custom Cache Validation](https://joblib.readthedocs.io/en/latest/memory.html#custom-cache-validation) : Joblib's documentation on custom cache validation, which allows for implementing a daily cache invalidation strategy.
- [Filesystem Spec Documentation](https://filesystem-spec.readthedocs.io/en/latest/index.html) : Documentation for Filesystem Spec (fsspec), a Python package providing a common interface to many file systems, including cloud storage solutions.
- [Freezegun GitHub Repository](https://github.com/spulec/freezegun) : GitHub repository for Freezegun, a package used for unit testing the @daily_cache decorator by freezing time.

## Topics

![[topics/Concept/fsspec]]

![[topics/Library/joblib]]

![[topics/Library/functools]]

![[topics/Library/FreezeGun]]