---
already_read: false
link: https://aeturrell.com/blog/posts/the-data-validation-landscape-in-2025/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2025-03-11'
---

https://aeturrell.com/blog/posts/the-data-validation-landscape-in-2025/
## Summary

Data validation is crucial for ensuring data quality in various contexts, including public sector analysis. Key points include:

- **Purpose of Data Validation**: It automates the checking of data quality by enforcing rules (e.g., datatype checks, missing values, value ranges) to avoid misinterpretation of data anomalies.

- **Tools for Data Validation**:
  1. **Great Expectations**: A robust, production-grade tool offering advanced features and integration options but may be complex for less tech-savvy users.
  2. **Pointblank**: A user-friendly, newer tool from Posit, ideal for individual users but currently lacks action triggers for failed validations.
  3. **Pandera**: Adopts a schema-based approach similar to Great Expectations, useful for detailed validation, and can integrate statistical hypothesis testing.
  4. **Pydantic**: Focuses on dictionary validation rather than dataframes, suitable for schema validation and complex object handling.
  5. **Cerberus**: Offers simple, lightweight validation functionality and is easily extensible.
  6. **jsonschema**: Specifically for JSON validation, simple and effective for ensuring data structure compliance.

- **Recommendations for Public Sector Use**: Choose tools based on specific needs—Pandera for dataframes in mixed skill teams, Great Expectations for production environments requiring automation, and Pydantic for validating user input from APIs.
## Links

- [Pandera Documentation](https://pandera.readthedocs.io/) : Official documentation for the Pandera library, which is used for validation of pandas DataFrames.
- [Great Expectations](https://greatexpectations.io/) : Website for Great Expectations, a data validation tool that helps you to create and maintain expectations on your data.
- [JSON Schema Validation with jsonschema](https://github.com/python-jsonschema/jsonschema) : GitHub repository for the `jsonschema` package, which allows for the validation of JSON data against a schema.
- [Pointblank Documentation](https://posit-dev.github.io/pointblank/) : Official documentation for Pointblank, a data validation package in Python that offers a user-friendly approach to validate data.
- [Pydantic Documentation](https://docs.pydantic.dev/) : Official documentation for Pydantic, a data validation library for Python that uses Python type annotations.

## Topics

![](topics/Concept/Data%20Validation)

![](topics/Library/Great%20Expectations)

![](topics/Library/Pointblank)

![](topics/Library/Pandera)

![](topics/Tool/Pydantic)

![](topics/Tool/Cerberus)

![](topics/Tool/jsonschema)