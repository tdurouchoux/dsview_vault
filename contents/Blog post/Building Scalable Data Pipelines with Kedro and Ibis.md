---
already_read: true
link: https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
read_priority: 0
source: null
tags:
- Data_Engineering
- Python
type: Content
upload_date: '2024-09-25'
---

https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
## Summary

The article discusses building scalable data pipelines using Kedro and Ibis, highlighting the challenges faced during the transition from development to production. Kedro is praised for its ability to facilitate collaboration among data teams and maintain software engineering principles, but it struggles with scaling when moving from development datasets to production databases.

Key points include:

- **Development vs. Production**: Kedro excels in the development phase but often requires significant rewrites for production, leading to performance issues and bugs.
- **SQL as a Standard**: SQL is a universal language for databases, and tools like dbt are recommended for data transformation workflows, especially for teams familiar with SQL.
- **Ibis Integration**: Ibis provides a Python dataframe API that allows users to write code that can execute across various query engines, combining the flexibility of Python with the performance of SQL.
- **Pipeline Development**: The article illustrates how to create a custom Ibis dataset in Kedro and develop pipelines using Ibis, showcasing the ease of integrating Ibis with Kedro for data processing tasks.
- **Future Enhancements**: The author mentions ongoing work to improve data validation and materialization features in Ibis and Kedro, as well as the potential for better deployment functionalities.

Overall, the integration of Ibis into Kedro workflows is presented as a solution to enhance the scalability and maintainability of data pipelines, allowing for more efficient data processing and feature engineering.
## Links

1. [Ibis Project](https://ibis-project.org/) - A Python library that provides a lightweight, universal interface for data wrangling, allowing execution against various query engines.
2. [Kedro Documentation](https://docs.kedro.org/en/stable/) - Official documentation for Kedro, a framework for building reproducible, maintainable, and modular data science code.
3. [Jaffle Shop GitHub Repository](https://github.com/dbt-labs/jaffle_shop) - A sample dbt project that serves as a playground for testing and demonstration purposes, relevant for understanding data transformation workflows.
4. [Kedro-Datasets Documentation](https://docs.kedro.org/projects/kedro-datasets/en/kedro-datasets-2.0.0/) - Documentation for Kedro's dataset management, which is crucial for handling data in Kedro pipelines.
5. [DBT Materializations Documentation](https://docs.getdbt.com/docs/build/materializations) - Information on how dbt handles materializations, which is important for understanding data transformation and storage in workflows.
## Topics

![](topics/Library/Kedro)

![](topics/Library/Ibis)

![](topics/Product/dbt)

![](topics/Concept/Data%20Pipeline)

![](topics/Concept/Data%20Validation)