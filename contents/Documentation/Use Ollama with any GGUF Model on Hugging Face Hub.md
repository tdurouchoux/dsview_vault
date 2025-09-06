---
already_read: true
link: https://huggingface.co/docs/hub/en/ollama
read_priority: 5
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2024-12-28'
---

https://huggingface.co/docs/hub/en/ollama
## Summary

The content provides instructions on using Ollama with GGUF models on the Hugging Face Hub. Key points include:

- **Ollama Integration**: Ollama, a llama.cpp-based application, can run any GGUF quant models from the Hugging Face Hub without creating a new Modelfile.
- **Getting Started**: Enable Ollama in Local Apps settings and use the `ollama run` command with the model's Hub URL.
- **Custom Quantization**: Users can select different quantization schemes by specifying the quantization tag in the `ollama run` command.
- **Custom Chat Template and Parameters**: Users can customize chat templates and parameters by creating specific files (template, system, params) in the model repository.
- **Private GGUFs**: To run private GGUFs, users need to add their Ollama SSH key to their Hugging Face account settings.

The content also includes example commands and references to relevant documentation.
## Links

- [Ollama GitHub Repository](https://github.com/ollama/ollama/blob/main/docs/README.md) : The official Ollama GitHub repository, containing documentation and resources for using Ollama with GGUF models.
- [GGUF Usage Documentation](https://huggingface.co/docs/hub/en/gguf) : Detailed documentation on GGUF usage with various tools, including Ollama, provided by Hugging Face.

## Topics

![](topics/Concept/GGUF)

![](topics/Platform/Hugging%20Face)

![](topics/Concept/Ollama)