---
already_read: true
link: https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
read_priority: 0
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2024-09-25'
---

https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
## Summary

The article discusses the integration of Kedro and Ibis for building scalable data pipelines. Kedro is acknowledged for its strong support during the proof-of-concept phase but faces challenges in production deployment, particularly with scaling data workflows. Teams often struggle to optimize existing code when transitioning from development to production databases, particularly when using tools like PySpark, which can underperform compared to direct execution on back-end engines.

The article advocates for the use of SQL for standardized data workflows and highlights dbt as a robust framework for SQL transformations. It contrasts the SQL approach with Python-centric workflows, suggesting that while teams may prefer Python, a balance can be achieved through Ibis—a Python library that abstracts data wrangling and provides a uniform interface to various data backends. 

The integration of Ibis into Kedro allows users to leverage both Python's flexibility and SQL's performance, enabling lazy execution and efficient data management. A practical example illustrates how to process data in a Kedro pipeline using Ibis, demonstrating its advantages in maintaining performance while simplifying workflow across various database environments.

Future extensions of this integration are discussed, including enhancements for data validation and DDL operations. The author encourages feedback on the tutorial and the overall pipeline production experience.
## Links

- [Kedro Documentation](https://docs.kedro.org/en/stable/introduction/index.html#introduction-to-kedro) : Official documentation for Kedro, a framework for creating reproducible, maintainable, and modular data science code.
- [What is dbt?](https://www.getdbt.com/product/what-is-dbt) : A concise overview of dbt (data build tool), a SQL-first framework for data transformation.
- [Jaffle Shop Example Repository](https://github.com/dbt-labs/jaffle_shop) : The dbt Jaffle Shop example repository used for testing and demonstration of dbt functionalities.
- [Ibis Project](https://ibis-project.org/) : Official website for the Ibis project, a Python library providing a universal interface for data wrangling across various query engines.
- [Kedro-Ibis Integration on GitHub](https://github.com/kedro-org/kedro-plugins/blob/kedro-datasets-2.0.0/kedro-datasets/kedro_datasets/pandas/sql_dataset.py) : Kedro integration with Ibis demonstrating how to configure backends for loading and saving data with Ibis.

## Topics

![](topics/Library/Kedro)

![](topics/Library/Ibis)

![](topics/Concept/Data%20Pipelines)

![](topics/Platform/dbt%20Data%20Build%20Tool)

![](topics/Concept/Lazy%20Evaluation)

![](topics/Concept/SQL%20Dialects)

![](topics/Library/DuckDB)