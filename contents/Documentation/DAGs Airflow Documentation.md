---
already_read: false
link: https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html
read_priority: 1
source: null
tags:
- MlOps
type: Content
upload_date: '2023-10-12'
---

https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html
## Summary

DAGs (Directed Acyclic Graphs) are central to Apache Airflow, defining the structure and execution order of tasks. Key concepts include:

- **Declaring a DAG**: DAGs can be declared using context managers, constructors, or decorators. Each DAG has a unique ID, start date, and schedule.
- **Task Dependencies**: Tasks within a DAG can have dependencies defined using operators (>> and <<) or methods (set_upstream, set_downstream).
- **Loading and Running DAGs**: Airflow loads DAGs from Python files in the configured DAG_FOLDER. DAGs can be triggered manually or run on a defined schedule.
- **Control Flow**: Control flow mechanisms include branching, trigger rules, and dependencies on past task runs.
- **Dynamic DAGs**: DAGs can be dynamically generated using loops and functions, allowing for flexible task definitions.
- **DAG Visualization**: Airflow provides a UI for visualizing DAGs, including task groups for better organization.
- **Documentation**: DAGs and tasks can include documentation that is rendered in the UI.
- **SubDAGs vs TaskGroups**: SubDAGs are deprecated in favor of TaskGroups, which provide a simpler way to group tasks without the overhead of a separate DAG.
- **Packaging and Ignoring DAGs**: Complex DAGs can be packaged into zip files, and the .airflowignore file can specify files or directories to ignore during DAG loading.
- **DAG Dependencies**: DAGs can depend on each other through triggering or waiting mechanisms.
- **DAG States**: DAGs can be paused, deactivated, or deleted, with specific procedures for managing their states.

Overall, Airflow provides a robust framework for orchestrating complex workflows through DAGs, emphasizing flexibility, visualization, and documentation.
## Links

1. [Apache Airflow GitHub Repository](https://github.com/apache/airflow) - The official repository for Apache Airflow, where you can find the source code, issues, and contributions.
2. [Apache Airflow Issues](https://github.com/apache/airflow/issues) - A page to track issues and feature requests for Apache Airflow, useful for developers and users to report bugs or request enhancements.
3. [Stack Overflow - Airflow Tag](https://stackoverflow.com/questions/tagged/airflow) - A community-driven Q&A platform where you can find discussions and solutions related to Apache Airflow.
4. [RE2 Syntax Documentation](https://github.com/google/re2/wiki/Syntax) - Documentation for the RE2 regular expression syntax, which is relevant for understanding patterns used in Airflow's .airflowignore file.
5. [Apache Software Foundation Security](https://www.apache.org/security/) - Information on security practices and policies for projects under the Apache Software Foundation, including Airflow.
## Topics

![](topics/Concept/DAGs)

![](topics/Library/Airflow)

![](topics/Concept/Task%20Dependencies)

![](topics/Concept/Dynamic%20DAGs)

![](topics/Concept/TaskGroups)