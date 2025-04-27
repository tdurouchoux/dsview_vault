---
already_read: true
link: https://huggingface.co/docs/hub/en/ollama
read_priority: 5
relevance: 0
source: Alpha Signal
tags:
- Data_Engineering
type: Content
upload_date: '2024-12-28'
---

https://huggingface.co/docs/hub/en/ollama
## Summary

Ollama is now compatible with any GGUF model available on the Hugging Face Hub, allowing users to run private GGUFs directly from their computers. With approximately 45,000 public GGUF checkpoints accessible, users can execute models with a straightforward command (`ollama run`). The application provides customization options including quantization type and system prompts.

Key features include:

1. **Running Models**: Users can select models from the Hugging Face Hub using the `Use this model` dropdown for Ollama.
2. **Custom Quantization**: Default quantization is Q4_K_M, but users can specify other quant types by modifying the command.
3. **Chat Templates**: By default, a chat template is automatically chosen. Users can create a custom template using a Go format and can adjust sampling parameters with a JSON file.
4. **Running Private GGUFs**: Users can execute private models from their Hugging Face accounts after adding their Ollama SSH key.

Overall, Ollama enhances accessibility and customization of GGUF models for users in data science.
## Links

- [Hugging Face Model Repository](https://huggingface.co/models?pipeline_tag=text-generation&library=gguf&sort=trending) : A collection of models hosted on the Hugging Face Hub, including those compatible with GGUF.
- [GGUF Documentation](https://huggingface.co/docs/hub/en/gguf) : Official documentation on GGUF (General Generalized Unified Format) usage and specifications.
- [Ollama GitHub Repository](https://github.com/ollama/ollama/blob/main/docs/README.md) : README document for the Ollama project, explaining its features and usage.
- [Ollama Template Documentation](https://github.com/ollama/ollama/blob/main/docs/template.md) : Documentation explaining how to create and customize chat templates for Ollama.
- [Hugging Face SSH Key Settings](https://huggingface.co/settings/keys) : Settings page for managing your SSH keys on Hugging Face for accessing private models.

## Topics

![](topics/Tool/Ollama)

![](topics/Library/llama%20cpp)

![](topics/Platform/Hugging%20Face)

![](topics/Concept/GGUF%20Generalized%20General%20Use%20Format)

![](topics/Tool/Quantization)

![](topics/Concept/Inference%20API)