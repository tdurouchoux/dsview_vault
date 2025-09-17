---
type: Concept
---

A Directed Acyclic Graph (DAG) is a data structure that consists of nodes and directed edges, where the edges have a direction and there are no cycles. In the context of Airflow, a DAG is used to define a workflow, where nodes represent tasks and edges represent dependencies between tasks. The DAG ensures that tasks are executed in a specific order, and it encapsulates everything needed to execute a workflow, including the schedule, tasks, task dependencies, callbacks, and additional parameters.