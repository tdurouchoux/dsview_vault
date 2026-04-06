---
type: Concept
---

Code serialization is the process of converting code or its execution state into a format that can be stored, transmitted, or later restored. This is useful for caching parsed code, suspending execution across process boundaries, or resuming execution in a different environment. Monty supports serialization of both the interpreter state and execution snapshots, allowing developers to save progress and resume execution at a later time or in a different process.