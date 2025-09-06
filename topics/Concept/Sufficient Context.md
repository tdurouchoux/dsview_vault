---
type: Concept
---

Sufficient context refers to the notion that the provided context contains enough information to answer a query definitively. This concept is crucial in evaluating the performance of RAG systems, as it helps determine whether errors arise because the LLM fails to utilize the context or because the context itself is insufficient. The sufficient context designation is a function of an input pair consisting of one question and the associated context, and it does not require a ground truth answer. The context is considered sufficient if it contains all the necessary information to provide a definitive answer, and insufficient if it does not or if the information is incomplete, inconclusive, or contradictory.