---
already_read: true
link: https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
read_priority: 0
relevance: 0
source: null
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2024-09-25'
---

https://kedro.org/blog/building-scalable-data-pipelines-with-kedro-and-ibis
## Summary

The article discusses integrating Kedro, a Python framework for building data pipelines, with Ibis, a Python library that provides a unified interface for data manipulation across various query engines. The main points include:

1. **Challenges with Kedro**: Kedro is excellent for prototyping but faces scalability issues when moving to production, especially with large datasets and direct database interactions.

2. **SQL as a Solution**: SQL is widely supported across databases and computation frameworks, making it a robust choice for data transformation workflows. dbt (data build tool) is highlighted as a popular SQL-first framework for this purpose.

3. **Ibis Integration**: Ibis allows Python code to execute against multiple query engines, combining the flexibility of Python with the performance of SQL. It supports deferred execution, pushing logic to the query engine and minimizing data movement.

4. **Implementation Example**: The article provides a detailed example of using Ibis with Kedro to create a data pipeline, demonstrating how to configure backends, build pipelines, and visualize the process. It also includes steps to try the implementation yourself.

5. **Benefits of Ibis**: Using Ibis with Kedro can simplify the productionization of data pipelines, make pipelines more reusable, and reduce the need for rewriting code when switching databases.

6. **Future Considerations**: The article mentions potential future work, such as implementing validations and exploring materialized views, and encourages feedback on the tutorial and pipeline productionization experience.

The article concludes by providing resources for further exploration and encouraging readers to share their thoughts and ideas.
## Links

- [Kedro Documentation](https://docs.kedro.org/en/stable/) : Official documentation for Kedro, providing comprehensive guides and references for using the Kedro framework.
- [Ibis Project GitHub](https://github.com/ibis-project/ibis) : GitHub repository for the Ibis project, a Python library that provides a lightweight, universal interface for data wrangling.
- [dbt Documentation](https://docs.getdbt.com/docs/build/materializations) : Documentation for dbt (data build tool), focusing on materializations, which is relevant for data transformation workflows.

## Topics

![[topics/Library/DuckDB]]

![[topics/Tool/Kedro]]

![[topics/Library/Ibis]]

![[topics/Library/Pandera]]

![[topics/Library/OmegaConf]]

![[topics/Library/Graphviz]]