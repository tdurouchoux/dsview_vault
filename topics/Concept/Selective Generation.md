---
type: Concept
---

Selective Generation is a method used to improve the performance of large language models (LLMs) by selectively generating responses based on the sufficiency of the context. This approach involves using a smaller, intervention model to determine when the LLM should generate a response or abstain, providing a controllable trade-off between accuracy and coverage. The method leverages sufficient context information to guide the abstention process, thereby reducing hallucinations and improving the overall accuracy of the model's responses. Selective generation can be combined with any LLM, including proprietary models like Gemini and GPT, and has been shown to improve the fraction of correct answers among the times where the model responds.