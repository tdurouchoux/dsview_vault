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

- **Data Validation**: Automated or semi-automated process to check data quality, ensuring accuracy in analysis and production of statistics.
- **Tools Comparison**:
  - **Great Expectations**: Production-grade, supports various data sources, advanced features like Slack notifications, but complex for non-expert teams.
  - **Pointblank**: User-friendly, supports multiple data sources, lacks action triggers for failed validations.
  - **Pandera**: Similar API to Great Expectations, supports statistical hypothesis testing, integrates with various data sources.
  - **Pydantic**: Validates dictionaries (e.g., JSON), not dataframes, flexible for non-tabular data, integrates with tools like FastAPI.
  - **Cerberus**: Lightweight, returns True/False for validations, uses text-based dictionaries for schemas.
  - **jsonschema**: Focuses on validating JSON, similar to Cerberus.
- **Recommendations for Public Sector**:
  - **Pandera**: Good for mixed teams, non-production environments.
  - **Great Expectations**: Better for production environments with automation needs.
  - **Pydantic**: Best for validating user input from APIs or forms.
## Links

- [Great Expectations](https://greatexpectations.io/) : Great Expectations is a heavy-duty production-grade data validation tool. It allows users to validate data quality in an automated or semi-automated way, checking datatypes, missing values, and anomalous numbers. It supports various data sources and offers advanced features like Slack notifications and data documentation updates.
- [Pandera](https://pandera.readthedocs.io/) : Pandera is a data validation tool that follows an API similar to Great Expectations. It supports column-level validation and statistical hypothesis testing. It is compatible with various data sources including Polars, geopandas, Pyspark, dark, and modin dataframes.
- [Pointblank](https://posit-dev.github.io/pointblank/) : Pointblank is a new data validation tool from Posit. It supports a wide range of data sources and offers a user-friendly interface for building validation plans. It is particularly geared towards individual institutional users.
- [Pydantic](https://docs.pydantic.dev/) : Pydantic is a data validation tool that focuses on schema validation for dictionaries, such as those ingested from JSON files. It is production-grade and integrates with other Python tools like FastAPI. It is particularly useful for validating non-tabular data and complex objects.
- [jsonschema](https://github.com/python-jsonschema/jsonschema) : jsonschema is a Python library for validating JSON data against a specified schema. It is similar to Cerberus and is specifically focused on validating JSON data. It provides powerful yet simple and lightweight data validation functionality out of the box and is designed to be easily extensible.

## Topics

![](topics/Library/Pydantic)

![](topics/Library/Cerberus)

![](topics/Library/jsonschema)

![](topics/Library/Great%20Expectations)

![](topics/Library/Pointblank)

![](topics/Library/Pandera)