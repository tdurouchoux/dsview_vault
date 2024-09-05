---
already_read: false
link: https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html
read_priority: 1
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2023-10-12'
---

https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html
## Summary

DAGs (Directed Acyclic Graphs) are central to Apache Airflow, defining the structure and execution order of tasks. Key concepts include:

- **Declaring a DAG**: DAGs can be declared using context managers, constructors, or decorators. Each DAG has a unique ID, start date, and schedule.
- **Task Dependencies**: Tasks within a DAG can have dependencies defined using operators (>> and <<) or methods (set_upstream, set_downstream).
- **Loading and Running DAGs**: Airflow loads DAGs from Python files in the configured DAG_FOLDER. DAGs can be triggered manually or run on a defined schedule.
- **DAG Assignment**: Each task must be assigned to a DAG, either implicitly or explicitly.
- **Control Flow**: Control flow mechanisms include branching, trigger rules, and dependencies on past task runs.
- **Dynamic DAGs**: DAGs can be generated dynamically using loops and functions.
- **DAG Visualization**: Airflow provides a UI for visualizing DAGs and their task states.
- **TaskGroups**: TaskGroups help organize tasks visually without creating separate DAGs, unlike deprecated SubDAGs.
- **DAG Documentation**: Documentation can be added to DAGs and tasks for clarity in the UI.
- **DAG Management**: DAGs can be paused, deactivated, or deleted, with specific procedures for each state.

Additional features include packaging DAGs, using .airflowignore files to exclude certain files, and managing DAG dependencies through operators like TriggerDagRunOperator and ExternalTaskSensor. The documentation also covers best practices, troubleshooting, and configuration options.
## Links

1. [RE2 Syntax Documentation](https://github.com/google/re2/wiki/Syntax) - Provides details on the syntax used for regular expressions in the RE2 library, which is relevant for understanding the .airflowignore file patterns.
2. [Apache Airflow GitHub Repository](https://github.com/apache/airflow) - The official repository for Apache Airflow, where you can find the source code, issues, and contributions related to Airflow.
3. [Apache Airflow Issues](https://github.com/apache/airflow/issues) - A place to report bugs, request features, and track issues related to Apache Airflow.
4. [Apache Airflow Documentation](https://airflow.apache.org/docs/) - The main documentation site for Apache Airflow, providing comprehensive guides and references for using Airflow effectively.
5. [Apache Airflow Slack Community](https://s.apache.org/airflow-slack) - A link to join the Apache Airflow community on Slack for discussions, support, and networking with other Airflow users.
## Topics

- [[topics/Concept/DAGs]]
- [[topics/Library/Airflow]]
- [[topics/Concept/Task Dependencies]]
- [[topics/Concept/Dynamic DAGs]]
- [[topics/Concept/TaskGroups]]