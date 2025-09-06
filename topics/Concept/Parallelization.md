---
type: Concept
---

Parallelization is a workflow pattern where LLMs work simultaneously on a task, with their outputs aggregated programmatically. This pattern has two key variations: sectioning, where a task is broken into independent subtasks run in parallel, and voting, where the same task is run multiple times to get diverse outputs. Parallelization is effective for tasks that can be divided for speed or require multiple perspectives for higher confidence results.