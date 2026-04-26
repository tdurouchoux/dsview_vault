---
type: Concept
---

The Ralph Loop is a specific harness pattern designed for long-horizon autonomous execution. It intercepts the model's exit attempts via hooks and reinjects the original prompt into a clean context window, forcing the agent to continue its work toward a completion goal. This loop relies on durable state management (e.g., filesystems) to maintain progress across iterations, ensuring agents can complete complex tasks over extended periods without losing coherence.