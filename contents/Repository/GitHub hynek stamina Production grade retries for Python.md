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

**stamina** is a Python library designed for production-grade retries, wrapping the unopinionated **Tenacity** package. It aims to be ergonomic, with sensible defaults to minimize misuse. Key features include:

- Retrying on specific exceptions or subsets via predicates.
- Exponential backoff with jitter between retries.
- Limits on retry attempts and total time.
- Automatic async support, including Trio.
- Preservation of type hints for decorated callables.
- Built-in instrumentation with Prometheus, structlog, and standard library logging.
- Dedicated testing support to deactivate retries globally or limit them.

Example usage:
```python
import httpx
import stamina

@stamina.retry(on=httpx.HTTPError, attempts=3)
def do_it(code: int) -> httpx.Response:
    resp = httpx.get(f"https://httpbin.org/status/{code}")
    resp.raise_for_status()
    return resp
```

The project is maintained by Hynek Schlawack, supported by Variomedia AG and GitHub Sponsors, and is distributed under the MIT license. It is also available as part of the Tidelift Subscription for enterprise support.
## Links

- [stamina Documentation](https://stamina.hynek.me/) : The official documentation for stamina, providing detailed information on how to use the library for production-grade retries in Python.
- [stamina Tutorial](https://stamina.hynek.me/en/latest/tutorial.html) : A tutorial on how to use stamina, including examples and best practices for implementing retries in Python applications.
- [stamina PyPI](https://pypi.org/project/stamina/) : The PyPI page for stamina, where you can find information about the package, including installation instructions and release notes.

## Topics

![](topics/Library/Stamina)

![](topics/Library/Tenacity)