---
already_read: true
link: https://huggingface.co/docs/hub/en/ollama
read_priority: 5
source: Alpha Signal
tags:
- Large_Language_Model
- Generative_AI
type: Content
upload_date: '2024-12-28'
---

https://huggingface.co/docs/hub/en/ollama
## Summary

Ollama can now be used with any GGUF model available on the Hugging Face Hub, allowing users to run private GGUFs directly from their local machines. Key features include:

- **Running Models**: Users can execute any of the 45K public GGUF checkpoints with a simple command (`ollama run hf.co/{username}/{repository}`).
- **Custom Quantization**: The default quantization scheme is Q4_K_M, but users can select different schemes by specifying them in the command.
- **Custom Chat Templates**: Users can create custom chat templates and configure system prompts and sampling parameters by adding specific files to the model repository.
- **Private GGUFs**: Users can run private models by adding their Ollama SSH key to their Hugging Face account.

Overall, Ollama enhances the interaction with GGUF models, providing flexibility in quantization and customization options.
## Links

1. [Ollama GitHub Repository](https://github.com/ollama/ollama/blob/main/docs/README.md) - Official documentation for Ollama, detailing its features and usage.
2. [GGUF Documentation](https://huggingface.co/docs/hub/en/gguf) - Comprehensive guide on GGUF (Generalized Generative Unified Format) and its applications.
3. [Ollama Template Documentation](https://github.com/ollama/ollama/blob/main/docs/template.md) - Instructions on how to create and customize chat templates for Ollama.
4. [Hugging Face Local Apps Settings](https://huggingface.co/settings/local-apps) - Settings page for managing local applications on Hugging Face, including Ollama.
5. [Ollama Modelfile Parameters](https://github.com/ollama/ollama/blob/main/docs/modelfile.md#parameter) - Documentation on parameters for configuring models in Ollama.
## Topics

![](topics/Tool/Ollama)

![](topics/Concept/GGUF)

![](topics/Platform/Hugging%20Face)

![](topics/Concept/Custom%20Quantization)

![](topics/Concept/Chat%20and%20RAG%20Templates)