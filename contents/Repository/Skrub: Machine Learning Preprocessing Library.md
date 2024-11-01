---
already_read: true
link: https://skrub-data.org/stable/
read_priority: 1
source: None
tags:
- Feature_Engineering
- Python
type: Content
upload_date: '2024-11-01'
---

https://skrub-data.org/stable/
## Summary

skrub is a Python library designed to simplify preprocessing and feature engineering for tabular machine learning, aiming to connect database tables directly to machine learning estimators. It is compatible with scikit-learn and supports Pandas and Polars dataframes, handling various data types including numeric, categorical, dates, text, and missing values.

Key features include:

- **Effortless Pipelines**: Create scikit-learn pipeline baselines easily using `TableVectorizer` and `tabular_learner`.
- **Powerful Feature Engineering**: Utilize `GapEncoder` and `MinHashEncoder` for encoding text and high cardinality categorical data, and `DatetimeEncoder` for extracting features from dates.
- **Interactive Data Exploration**: Use `TableReport` for interactive exploration of dataframes.

The library encourages community contributions and aims to reduce the amount of code needed for data wrangling, allowing data scientists to focus more on machine learning tasks.
## Links

1. [GitHub](https://github.com/skrub-data/skrub/) - The official repository for the skrub library, where you can find the source code, documentation, and contribute to the project.
2. [Cramér's V](https://en.wikipedia.org/wiki/Cram%C3%A9r%27s_V) - A statistical measure of association between two nominal variables, useful for understanding relationships in categorical data.
## Topics

- [[topics/Library/skrub]]
- [[topics/Library/TableVectorizer]]
- [[topics/Library/tabular_learner]]
- [[topics/Library/GapEncoder]]
- [[topics/Library/TableReport]]