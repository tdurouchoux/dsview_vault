---
type: Concept
---

DAG Pausing, Deactivation, and Deletion are states and actions related to the lifecycle management of DAGs in Airflow. Pausing a DAG stops it from being scheduled but allows running tasks to complete. Deactivating a DAG involves removing it from the DAGS_FOLDER, which stops the scheduler from processing it but retains its metadata. Deleting a DAG involves removing its metadata from the database, which can be done via the UI or API. Proper management of these states ensures efficient workflow management and resource utilization.