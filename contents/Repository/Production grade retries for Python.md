---
already_read: false
link: https://github.com/hynek/stamina
read_priority: 4
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2025-02-21'
---

https://github.com/hynek/stamina
## Summary

Stamina is a Python library designed to simplify and standardize retry mechanisms for handling transient failures in distributed systems. It is an opinionated wrapper around the Tenacity library, aiming to provide ergonomic and safe retry configurations by default. Key features include:

- **Selective Retry**: Retry only on specific exceptions or subsets of them using predicates.
- **Exponential Backoff with Jitter**: Automatically implements exponential backoff with jitter between retries to avoid thundering herd problems.
- **Retry Limits**: Limits the number of retries and total time to prevent infinite retries.
- **Async Support**: Automatic support for asynchronous operations, including Trio.
- **Type Hints**: Preserves type hints of the decorated callable.
- **Instrumentation**: Built-in support for Prometheus, structlog, and standard library logging.
- **Testing Support**: Dedicated features for testing, such as globally deactivating retries or limiting retries and removing backoffs.

The library is distributed under the MIT license and is supported by Variomedia AG and GitHub Sponsors. It is also available as part of the Tidelift Subscription for enterprise support. The project includes comprehensive documentation, a changelog, and example tutorials.
## Links

- [Stamina Documentation](https://stamina.hynek.me/) : The official documentation for Stamina, providing detailed information on how to use the library for production-grade retries in Python.
- [Stamina Tutorial](https://stamina.hynek.me/en/latest/tutorial.html) : A tutorial on how to use Stamina for implementing retries in Python applications.
- [Stamina PyPI](https://pypi.org/project/stamina/) : The PyPI page for Stamina, where you can find information on installing and using the package.

## Topics

![[topics/Library/Tenacity)]]

![[topics/Library/Stamina)]]