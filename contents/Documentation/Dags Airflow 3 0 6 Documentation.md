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

The content provides a comprehensive overview of Directed Acyclic Graphs (DAGs) in Apache Airflow, focusing on version 3.0.6. Here are the key technical points and takeaways:

1. **DAG Overview**:
   - A DAG encapsulates everything needed to execute a workflow, including schedule, tasks, task dependencies, callbacks, and additional parameters.
   - DAGs are defined using Python code and can be declared using context managers, constructors, or decorators.

2. **Task Dependencies**:
   - Tasks within a DAG can have dependencies on other tasks, which are declared using operators (`>>`, `<<`) or methods (`set_upstream`, `set_downstream`).
   - Complex dependencies can be managed using `cross_downstream` and `chain`.

3. **Loading and Running DAGs**:
   - Airflow loads DAGs from Python files, executing them to load DAG objects.
   - DAGs can be triggered manually, via API, or on a defined schedule.
   - Each DAG run creates a new instance with a defined data interval.

4. **DAG Assignment and Default Arguments**:
   - Tasks must be assigned to a DAG, either implicitly or explicitly.
   - Default arguments can be applied to all tasks within a DAG.

5. **Control Flow**:
   - Control flow mechanisms include branching, trigger rules, setup and teardown tasks, and dynamic DAGs.
   - Branching allows selecting tasks based on conditions, while trigger rules define when tasks should run.

6. **DAG Visualization**:
   - DAGs can be visualized using the Airflow UI or the `airflow dags show` command.
   - TaskGroups and Edge Labels help organize and label tasks for better visualization.

7. **Documentation and Packaging**:
   - Documentation can be added to DAGs and tasks, visible in the web interface.
   - DAGs can be packaged as zip files, but with certain caveats.

8. **DAG Management**:
   - DAGs can be paused, deactivated, or deleted, with different implications for each state.
   - Auto-pausing can be configured based on the number of consecutive failed runs.

9. **DAG Dependencies**:
   - Dependencies between DAGs can be managed using `TriggerDagRunOperator` and `ExternalTaskSensor`.
   - The DAG Dependencies view helps visualize these relationships.

10. **Configuration and Ignore Files**:
    - `.airflowignore` files can be used to specify files or directories that Airflow should ignore.
    - The syntax for `.airflowignore` can be configured to use glob or regexp patterns.

This summary captures the main technical points and key takeaways from the provided content, focusing on the core concepts and functionalities of DAGs in Apache Airflow.
## Links

- [Apache Airflow GitHub Repository](https://github.com/apache/airflow) : The official GitHub repository for Apache Airflow, where you can find the source code, contribute to the project, and report issues.
- [Airflow Summit](https://airflowsummit.org) : The official website for the Airflow Summit, an event dedicated to Apache Airflow, featuring talks, workshops, and networking opportunities for the Airflow community.

## Topics

![](topics/Concept/Directed%20Acyclic%20Graph%20DAG)

![](topics/Concept/Task%20Dependencies)

![](topics/Concept/TaskGroups)

![](topics/Concept/Edge%20Labels)

![](topics/Concept/DAG%20Visualization)

![](topics/Concept/DAG%20Documentation)

![](topics/Concept/DAG%20Dependencies)

![](topics/Concept/DAG%20Pausing%20Deactivation%20and%20Deletion)

![](topics/Concept/DAG%20Auto%20pausing)