---
type: Concept
---

DAG Auto-pausing is an experimental feature in Airflow that allows DAGs to be automatically paused if they fail a specified number of times consecutively. This feature helps in managing workflows by automatically disabling DAGs that consistently fail, preventing them from consuming resources and causing further issues. The auto-pausing behavior can be configured using Airflow configurations or overridden at the DAG level.