---
type: Concept
---

DAG Dependencies refer to the relationships between different DAGs in Airflow, where one DAG can depend on another. These dependencies can be of two types: triggering, where one DAG triggers the execution of another, and waiting, where one DAG waits for the completion of another. DAG Dependencies are visualized in the DAG Dependencies view and are calculated by the scheduler during DAG serialization.