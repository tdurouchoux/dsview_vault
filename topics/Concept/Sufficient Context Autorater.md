---
type: Concept
---

A sufficient context autorater is a model that evaluates instances based on the property of sufficient context. It classifies instances as having sufficient or insufficient context to answer a query. The autorater uses an LLM to label instances based on the definition of sufficient context, which involves determining whether the context contains enough information to construct an answer to the query. The autorater achieves high accuracy and operates without needing a ground truth answer, making it a valuable tool for analyzing model responses and datasets in RAG systems.