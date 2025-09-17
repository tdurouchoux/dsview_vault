---
type: Library
---

Stamina is a Python library designed to simplify the process of implementing production-grade retries. It is an opinionated wrapper around the Tenacity library, aiming to provide ergonomic and safe retry mechanisms by default. Stamina supports features like retrying on specific exceptions, exponential backoff with jitter, and flexible instrumentation with Prometheus, structlog, and standard library logging. It also includes dedicated support for testing and preserves type hints of the decorated callable.