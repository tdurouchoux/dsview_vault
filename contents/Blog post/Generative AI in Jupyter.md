---
already_read: false
link: https://blog.jupyter.org/generative-ai-in-jupyter-3f7174824862
read_priority: 1
source: null
tags:
- Generative_AI
- Python
type: Content
upload_date: '2023-09-14'
---

https://blog.jupyter.org/generative-ai-in-jupyter-3f7174824862
## Summary

Jupyter AI is an open-source project that integrates generative AI capabilities into Jupyter notebooks, enabling users to explain and generate code, fix errors, summarize content, and create entire notebooks from natural language prompts. It connects with various large language models (LLMs) from providers like AI21, Anthropic, AWS, Cohere, and OpenAI, utilizing LangChain for model support and local model integration.

Key features include:
- **Magic Commands and Chat Interface**: Users can interact with LLMs through a chat UI or by using magic commands in notebooks.
- **Data Privacy**: Jupyter AI prioritizes responsible AI use, allowing users to choose LLMs and ensuring data is only sent to models upon explicit request.
- **Notebook Generation**: Users can generate notebooks from text prompts and ask questions about local files using commands like /generate and /learn.
- **Error Handling**: The system can explain and correct code errors using the special Err variable.

Installation is straightforward via pip, and users must authenticate with model providers. The project is designed to be modular, extensible, and ethically responsible, with ongoing community contributions encouraged.
## Links

1. [Jupyter AI](https://github.com/jupyterlab/jupyter-ai) - The official GitHub repository for Jupyter AI, an open-source project that integrates generative AI into Jupyter notebooks.
2. [User Documentation](https://jupyter-ai.readthedocs.io/en/latest/users/index.html#model-providers) - Comprehensive user documentation for Jupyter AI, detailing how to configure and use the tool.
3. [Configuring Model Providers](https://jupyter-ai.readthedocs.io/en/latest/users/index.html#model-providers) - Specific section in the user documentation that explains how to set up various model providers for Jupyter AI.
4. [A List of Issues](https://github.com/jupyterlab/jupyter-ai/issues) - A GitHub page listing issues and feature requests for Jupyter AI, where users can contribute to the project.
5. [Adding Support for Locally Hosted LLMs](https://github.com/jupyterlab/jupyter-ai/issues/190) - A specific issue on GitHub discussing the addition of support for locally hosted large language models in Jupyter AI.
## Topics

- [[topics/Library/Jupyter AI]]
- [[topics/Library/LangChain]]
- [[topics/Concept/Magic Commands]]
- [[topics/Concept/Jupyternaut]]
- [[topics/Concept/Retrieval Augmented Generation (RAG)]]