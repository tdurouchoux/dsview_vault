---
type: Concept
---

Task Dependencies refer to the relationships between tasks in a workflow, defining the order and conditions under which tasks execute. In Airflow, task dependencies can be declared using operators like >> and <<, or methods like set_upstream and set_downstream. These dependencies form the structure of the DAG, ensuring tasks run in the correct sequence and under specified conditions.