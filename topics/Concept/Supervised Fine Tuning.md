---
type: Concept
---

Supervised Fine-Tuning (SFT) is a method used to adapt pre-trained language models to specific tasks by fine-tuning them on a labeled dataset. This process helps the model to better understand and generate responses that are more accurate and relevant to the task at hand. In ZeroSearch, SFT is used to transform the LLM into a retrieval module capable of generating both useful and noisy documents in response to queries. This process involves training the model on input-output pairs to improve its performance on particular tasks. In the context of SmolLM2, SFT was used to develop the instruct version of the model, leveraging both public datasets and curated datasets to enhance its capabilities in tasks such as text rewriting, summarization, and function calling.