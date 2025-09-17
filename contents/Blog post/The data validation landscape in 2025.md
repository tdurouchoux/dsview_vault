---
already_read: false
link: https://aeturrell.com/blog/posts/the-data-validation-landscape-in-2025/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Data_Quality
- Data_Engineering
type: Content
upload_date: '2025-03-11'
---

https://aeturrell.com/blog/posts/the-data-validation-landscape-in-2025/
## Summary

**Summary:**

- **Data Validation**: Automated or semi-automated process to check data quality, such as data types, missing values, and anomalies. It can be used for dataframes, API inputs, or form submissions.

- **Usefulness in Public Sector**: Data validation is crucial for both ad hoc analysis and regular production of statistics. It helps ensure data accuracy and efficiency, reducing the risk of errors in analysis.

- **Data Validation Tools**:

  1. **Great Expectations**: A production-grade tool with advanced features like Slack notifications on validation failures. It supports various data sources and has numerous expectations. However, it may be complex for teams with limited data science skills.

  2. **Pointblank**: A newer tool with a user-friendly syntax, supporting a wide range of data sources. It lacks action triggers for failed validations, requiring manual or custom-coded next actions.

  3. **Pandera**: Similar API to Great Expectations, supports column-level validation and statistical hypothesis testing. It integrates with various data sources and throws errors on validation failures.

  4. **Pydantic**: Validates dictionaries (e.g., JSON files) rather than dataframes. It uses classes to define schemas and is suitable for non-tabular data and API/user input validation.

  5. **Cerberus**: A lightweight tool with text-based dictionary schemas. It returns True or False for validations and is less fully featured than Pydantic.

  6. **jsonschema**: Focuses on validating JSON data, similar to Cerberus. It throws ValidationError exceptions on failures.

- **Recommendations for Public Sector**: The choice of tool depends on the use case. Pandera is recommended for mixed teams and non-production environments, Great Expectations for production environments, and Pydantic for user input validation. Pointblank is also promising and worth monitoring for future developments.
## Links

- [Great Expectations](https://greatexpectations.io/) : Great Expectations is a data validation tool mentioned in the article. It is a production-grade tool with advanced features like Slack notifications and database integration.
- [Pointblank](https://posit-dev.github.io/pointblank/) : Pointblank is a new data validation tool highlighted in the article. It supports various data sources and is noted for its user-friendly syntax.
- [Pandera](https://pandera.readthedocs.io/) : Pandera is a data validation library that integrates with multiple data sources and supports statistical hypothesis testing.
- [Pydantic](https://docs.pydantic.dev/) : Pydantic is a data validation tool focused on schema validation for dictionaries and non-tabular data, useful for API and form input validation.
- [jsonschema](https://github.com/python-jsonschema/jsonschema) : jsonschema is a Python library for validating JSON data against a specified schema, ensuring data integrity and correctness.

## Topics

![](topics/Library/Pydantic)

![](topics/Library/Cerberus)

![](topics/Library/jsonschema)

![](topics/Library/Great%20Expectations)

![](topics/Library/Pointblank)

![](topics/Library/Pandera)