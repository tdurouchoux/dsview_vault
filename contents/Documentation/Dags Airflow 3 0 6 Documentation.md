---
already_read: false
link: https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2023-10-12'
---

https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html
## Summary

A DAG (Directed Acyclic Graph) in Airflow encapsulates everything needed to execute a workflow, including schedule, tasks, task dependencies, callbacks, and additional parameters. DAGs can be declared using a context manager, a standard constructor, or a decorator. Task dependencies can be defined using operators like >> and <<, or methods like set_upstream and set_downstream. Airflow loads DAGs from Python files, and DAG runs can be triggered manually or via a schedule. Each DAG run creates a new instance with a data interval, and tasks within a DAG are instantiated into Task Instances. DAGs can be paused, deactivated, or deleted, with different implications for their metadata and historical runs. Airflow also supports dynamic DAGs, DAG visualization, and DAG dependencies. The DAG decorator allows for creating DAGs as functions, and control flow can be managed using branching, trigger rules, and setup/teardown tasks. Documentation can be added to DAGs and tasks for better understanding and management.
## Links

- [Apache Airflow GitHub Repository](https://github.com/apache/airflow) : The official GitHub repository for Apache Airflow, where you can find the source code, contribute to the project, and report issues.
- [Apache Airflow Documentation Edit Page](https://github.com/apache/airflow/edit/main/airflow-core/docs/core-concepts/dags.rst) : The GitHub page for editing the Apache Airflow documentation on DAGs, allowing users to suggest changes and improvements.

## Topics

![](topics/Concept/Directed%20Acyclic%20Graph%20DAG)

![](topics/Concept/Airflow)

![](topics/Concept/Task%20Dependencies)

![](topics/Concept/TaskGroups)

![](topics/Concept/Edge%20Labels)