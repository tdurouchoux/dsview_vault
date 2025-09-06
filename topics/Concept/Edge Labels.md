---
type: Concept
---

Edge Labels are used in Airflow to label the dependency edges between different tasks in the Graph view. They are particularly useful for branching areas of a DAG, allowing you to label the conditions under which certain branches might run. Edge Labels can be added directly inline with the >> and << operators or passed to set_upstream/set_downstream methods.