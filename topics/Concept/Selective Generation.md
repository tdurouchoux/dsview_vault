---
type: Concept
---

Selective generation is a method used to reduce hallucinations in RAG systems by leveraging sufficient context information for guided abstention. This approach involves using a smaller, intervention model to determine when the model should generate an answer or abstain, providing a controllable trade-off between accuracy and coverage. The selective generation framework improves the fraction of correct answers among the times where the model responds, leading to higher accuracy over the fraction of answered queries. This method can be combined with any LLM, including proprietary models like Gemini and GPT, and does not require fine-tuning.