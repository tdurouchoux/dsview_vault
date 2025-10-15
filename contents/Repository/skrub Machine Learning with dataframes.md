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

skrub is a Python library designed to simplify preprocessing and feature engineering for tabular machine learning, with a focus on integrating database tables directly into the machine learning workflow. It is compatible with scikit-learn and supports heterogeneous Pandas and Polars dataframes, including numeric, categorical, dates, and text data.

Key features of skrub include:

1. **Effortless Tabular Learning**: The library provides tools like `TableVectorizer` and `tabular_pipeline` to create strong scikit-learn pipeline baselines with minimal code.

2. **Interactive Data Exploration**: The `TableReport` feature allows for interactive exploration of dataframes, enabling users to gain insights and understand their data better.

3. **Powerful Feature Engineering**: skrub offers various encoders such as `StringEncoder`, `TextEncoder`, `GapEncoder`, and `MinHashEncoder` for encoding text and high cardinality categorical data. It also includes `DatetimeEncoder` for extracting features from dates.

4. **Tuning and Inspection**: Users can chain an arbitrary set of operations to prepare, transform, and assemble multiple tables for machine learning. The library supports tuning the full pipeline, inspecting it, or applying it to new data, and works with any computational or dataframe engine.

5. **Community and Contribution**: skrub is powered by a global community of contributors, and users are encouraged to join and contribute to the project.

The library aims to reduce the amount of code needed for data preprocessing and feature engineering, making it easier to get insights and build machine learning models.
## Links

- [skrub GitHub Repository](https://github.com/skrub-data/skrub/) : The GitHub repository for skrub, where you can find the source code, contribute to the project, and access the latest updates.

## Topics

![[topics/Concept/Feature Engineering]]

![[topics/Library/skrub]]

![[topics/Concept/Machine Learning]]

![[topics/Concept/Data Preprocessing]]

![[topics/Concept/Exploratory Data Analysis EDA]]

![[topics/Concept/Data Cleaning]]