---
already_read: false
link: https://github.com/hynek/stamina
read_priority: 4
relevance: 0
source: null
tags:
- Python
type: Content
upload_date: '2025-02-21'
---

https://github.com/hynek/stamina
## Summary

stamina is a Python library designed for implementing production-grade retries in distributed systems, addressing the common issue of transient failures. It serves as a user-friendly wrapper around the Tenacity package, focusing on ergonomic use while minimizing misuse. Key features include:

- Retry on specific exceptions, with the ability to filter them using predicates.
- Exponential backoff with jitter between retries.
- Configurable limits on the number of retries and total retry time.
- Support for asynchronous operations, including Trio.
- Preservation of type hints for decorated functions.
- Built-in instrumentation support for Prometheus, structlog, and standard logging.
- Testing capabilities that allow for global deactivation of retries or modification of retry parameters.

The library is open-source, licensed under MIT, and is actively maintained. It is suitable for both synchronous and asynchronous functions, making it versatile for various applications.
## Links

1. [Tenacity Documentation](https://tenacity.readthedocs.io/) - Official documentation for the Tenacity library, which is the foundation for the Stamina package.
2. [Stamina on PyPI](https://pypi.org/project/stamina/) - The Python Package Index page for Stamina, where you can find installation instructions and additional details.
3. [Structlog Documentation](https://www.structlog.org/) - Documentation for Structlog, a structured logging library that can be used with Stamina for better logging capabilities.
4. [Trio Documentation](https://trio.readthedocs.io/) - Official documentation for Trio, an async library that Stamina supports for asynchronous retries.
5. [Stamina Tutorial](https://stamina.hynek.me/en/latest/tutorial.html) - A tutorial for using Stamina, providing practical examples and usage patterns.
## Topics

![](topics/Library/stamina)

![](topics/Concept/Retries)

![](topics/Concept/Exponential%20Backoff)

![](topics/Tool/Tenacity)

![](topics/Platform/Prometheus)