---
already_read: true
link: https://narwhals-dev.github.io/narwhals/
read_priority: 0
relevance: 5
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2025-06-15'
---

https://narwhals-dev.github.io/narwhals/
## Summary

Narwhals is a lightweight and extensible compatibility layer for various DataFrame libraries such as cuDF, Modin, pandas, Polars, and PyArrow. It supports lazy data processing with frameworks like Dask and PySpark and aims to provide a unified API experience without introducing additional dependencies. Key features include:

- Use a subset of the Polars API, ensuring no need for additional learning.
- Zero dependencies, maintaining a lightweight library.
- Separate APIs for eager and lazy execution, enabling expression-based operations.
- Support for pandas' complex type system and index without conflicts.
- Comprehensive testing against nightly builds of pandas and Polars with negligible overhead.
- Fully typed system for better IDE support and a perfect backwards compatibility policy.

The roadmap for Narwhals can be accessed on GitHub for insights into future developments. It is designed for developers looking to create library or application services that interact with DataFrames in a framework-agnostic manner.
## Links

- [Narwhals on PyPI](https://pypi.org/project/narwhals) : The official Python Package Index page for the Narwhals library, providing installation details and package information.
- [Narwhals GitHub Repository](https://github.com/narwhals-dev/narwhals.git) : The GitHub repository for Narwhals, where you can find the source code, documentation, and community discussions.
- [PEP 740 - Type Hints for Python 3.10](https://peps.python.org/pep-0740/) : A Python Enhancement Proposal that discusses new type hinting strategies, could be relevant for developing types in libraries like Narwhals.
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) : A documentation theme for MkDocs that provides built-in support for styling and navigation, useful for creating documentation for projects like Narwhals.
- [Narwhals on Pepy](https://pepy.tech/project/narwhals) : A site providing download statistics and insights into the Narwhals Python package.

## Topics

![](topics/Library/Narwhals)

![](topics/Concept/DataFrame%20Agnosticism)

![](topics/Concept/Lazy%20Evaluation)

![](topics/Concept/Backward%20Compatibility)

![](topics/Library/Dask)

![](topics/Library/Polars)