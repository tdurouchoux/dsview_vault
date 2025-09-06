---
type: Concept
---

TaskGroups are a feature in Airflow that allows for the organization of tasks into hierarchical groups within a DAG. They help in reducing visual clutter and creating repeating patterns in the DAG structure. Tasks within a TaskGroup live on the same DAG and honor all DAG settings and pool configurations. TaskGroups can be used to apply dependency relationships across all tasks within the group.