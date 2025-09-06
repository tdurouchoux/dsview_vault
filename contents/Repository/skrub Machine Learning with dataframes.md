---
already_read: true
link: https://skrub-data.org/stable/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
- Feature_Engineering
type: Content
upload_date: '2024-11-01'
---

https://skrub-data.org/stable/
## Summary

skrub is a Python library designed to simplify preprocessing and feature engineering for tabular machine learning, with a focus on integrating database tables directly into the machine learning workflow. It is compatible with scikit-learn and supports both Pandas and Polars dataframes, handling various data types including numeric, categorical, dates, and text.

Key features include:

1. **Effortless Tabular Learning**: The library provides tools like `TableVectorizer` and `tabular_pipeline` to create strong baseline pipelines for machine learning tasks.

2. **Interactive Data Exploration**: The `TableReport` tool allows for interactive exploration of dataframes, aiding in data understanding and preprocessing.

3. **Powerful Feature Engineering**: skrub offers encoders for text and high cardinality categorical data, such as `StringEncoder`, `TextEncoder`, `GapEncoder`, and `MinHashEncoder`, as well as `DatetimeEncoder` for extracting features from dates.

4. **Flexible Data Wrangling**: Users can chain an arbitrary set of operations to prepare, transform, and assemble multiple tables for machine learning. This pipeline can then be tuned, inspected, or applied to new data, and it works with any computational or dataframe engine.

5. **Community-Driven**: The project is supported by a global community of contributors, fostering collaboration and continuous improvement.

Overall, skrub aims to reduce the amount of code needed for data preprocessing and feature engineering, making it easier to gain insights from tabular data.
## Links

- [skrub GitHub Repository](https://github.com/skrub-data/skrub/) : The GitHub repository for skrub, where you can find the source code, contribute to the project, and explore the latest updates.

## Topics

![](topics/Library/skrub)

![](topics/Concept/Tabular%20Machine%20Learning)

![](topics/Concept/TableVectorizer)

![](topics/Concept/TableReport)

![](topics/Concept/Feature%20Engineering)