---
already_read: true
link: https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
read_priority: 0
source: Aucune
tags:
- Data_Engineering
type: Content
upload_date: '2024-09-25'
---

https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
## Summary

The article discusses building scalable data pipelines using Kedro and Ibis, highlighting the challenges faced during the transition from development to production. Kedro is praised for its ability to facilitate collaboration among data engineers, scientists, and machine learning engineers, but it often struggles with scaling when moving from development datasets to production databases.

Key points include:

- **Development vs. Production**: Kedro excels in the proof-of-concept phase but can falter in production due to increased data volumes and the need for performance optimization.
- **SQL as a Standard**: SQL is a universal language for databases, and tools like dbt are recommended for data transformation workflows. Kedro and dbt share goals of reproducibility and maintainability.
- **Ibis Integration**: Ibis provides a Python dataframe API that allows users to write code that can execute across various query engines, combining Python's flexibility with SQL's performance. It supports lazy execution, optimizing data handling.
- **Pipeline Development**: The article illustrates how to create a custom Ibis dataset in Kedro and develop pipelines using Ibis, showcasing a comparison with dbt models.
- **Future Considerations**: While Ibis enhances pipeline productionization, it currently lacks some features like validations and certain DDL operations found in dbt. The author hints at future developments to address these gaps.

Overall, the integration of Ibis into Kedro workflows is presented as a solution to improve the scalability and efficiency of data pipelines, particularly for teams that prefer Python over SQL.
## Links

1. [Kedro Documentation](https://docs.kedro.org/en/stable/) - Official documentation for Kedro, a framework for building data pipelines.
2. [Ibis GitHub Repository](https://github.com/ibis-project/ibis) - The official repository for Ibis, a Python library for data wrangling with a universal interface.
3. [dbt GitHub Repository](https://github.com/dbt-labs/jaffle_shop) - A sample project for dbt, showcasing SQL-first transformation workflows.
4. [pandas API on Spark](https://spark.apache.org/docs/latest/api/python/user_guide/pandas_on_spark/index.html) - Documentation for using pandas API with Apache Spark, useful for data processing.
5. [BigQuery DataFrames](https://voltrondata.com/resources/google-bigframes-ibis) - Resource discussing the integration of Ibis with Google BigQuery for efficient data processing.
## Topics

- [[topics/Library/Kedro]]
- [[topics/Library/Ibis]]
- [[topics/Concept/Data Pipeline]]
- [[topics/Concept/SQL]]
- [[topics/Library/dbt]]