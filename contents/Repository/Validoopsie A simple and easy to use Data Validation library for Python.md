---
already_read: false
link: https://github.com/akmalsoliev/Validoopsie
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2025-02-25'
---

https://github.com/akmalsoliev/Validoopsie
## Summary

Validoopsie is a lightweight and user-friendly data validation library for Python, designed to simplify the data validation process. It allows users to declare classes and chain validations together, similar to popular DataFrame libraries. Key features include:

- **Bring Your Own DataFrame (BYOD)**: Supports any DataFrame that Narwhals supports.
- **Simple Syntax**: Each validation function is encapsulated in its own method, making it easy to chain validations together.
- **Inspired by Great Expectations**: Aims to simplify data validation tasks.
- **Impact Levels**: Errors are only raised if the impact level is set to high.
- **Development Tools**: Includes a Makefile for setting up dependencies, running linters, and tests.

Example usage:
```python
import pandas as pd
from validoopsie import Validate

p_df = pd.DataFrame({
    "name": ["John", "Doe", "Jane"],
    "target_name": ["John", "Doe", "Jane"],
    "last_name": ["Smith", "Smith", "Smith"],
    "age": [25, 30, 35],
})

vd = Validate(p_df)
vd.EqualityValidation.PairColumnEquality(
    column="name",
    target_column="age",
    impact="high",
).UniqueValidation.ColumnUniqueValuesToBeInList(
    column="last_name",
    values=["Smith"],
).ValuesValidation.ColumnValuesToBeBetween(
    column="age",
    min_value=20,
    max_value=40,
).validate()
```

Validoopsie is licensed under the MIT license and is available on GitHub.
## Links

- [Narwhals](https://github.com/narwhals-dev/narwhals) : Narwhals is a library that supports the Bring Your Own DataFrame (BYOD) concept, allowing users to use any DataFrame for data validation tasks.
- [Validoopsie Documentation](https://akmalsoliev.github.io/Validoopsie/) : The official documentation for Validoopsie, providing detailed information on how to use the library, including installation, getting started, development, and contribution guidelines.

## Topics

![](topics/Library/Validoopsie)