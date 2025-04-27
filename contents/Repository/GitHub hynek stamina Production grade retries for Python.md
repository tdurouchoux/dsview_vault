---
already_read: false
link: https://github.com/hynek/stamina
read_priority: 4
relevance: 0
source: null
tags:
- Python
- Data_Engineering
- DevOps
type: Content
upload_date: '2025-02-21'
---

https://github.com/hynek/stamina
## Summary

stamina is a Python library designed for implementing production-grade retry mechanisms efficiently. It serves as a wrapper around the Tenacity package to enhance usability while minimizing potential misuse. Key features include:

- Retry on specific exceptions, with the option to filter them using predicates.
- Exponential backoff with jitter for retries.
- Configurable limits on the number of retries and total retry time.
- Automatic support for asynchronous functions, including Trio compatibility.
- Preservation of type hints for the decorated functions.
- Built-in support for logging and instrumentation using Prometheus, structlog, and standard library logging.
- Special testing capabilities to control retry behavior during tests.

The library is intended to simplify error handling in distributed systems, providing a more ergonomic and safer retry implementation. It is licensed under the MIT license and maintained by Hynek Schlawack with support from Variomedia AG and Tidelift Subscription offerings for commercial support.
## Links

- [Tenacity Documentation](https://tenacity.readthedocs.io/) : Documentation for the Tenacity package, which provides a framework for retrying function calls.
- [Stamina Project Documentation](https://stamina.hynek.me/) : Official documentation for the Stamina package, outlining its features and usage.
- [Prometheus Python Client](https://github.com/prometheus/client_python) : Python client for Prometheus that allows you to instrument your Python applications.
- [PyPI - Stamina](https://pypi.org/project/stamina/) : The package page for Stamina on PyPI, where you can find installation instructions and package details.
- [Trio Documentation](https://trio.readthedocs.io/) : Documentation for Trio, a Python Async library that Stamina supports for automatic async retries.

## Topics

![](topics/Library/stamina)

![](topics/Concept/Retries%20in%20Distributed%20Systems)

![](topics/Concept/Exponential%20Backoff)

![](topics/Concept/Error%20Handling)