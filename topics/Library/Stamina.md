---
type: Library
---

Stamina is a production-grade retries library for Python. It is an opinionated wrapper around the Tenacity package, designed to make retrying failed operations in distributed systems easier and more resilient. Stamina aims to be ergonomic, doing the right thing by default, and minimizing the potential for misuse. It supports features like retrying on certain exceptions, exponential backoff with jitter, limiting the number of retries and total time, automatic async support, preserving type hints, and flexible instrumentation with Prometheus, structlog, and standard library logging.