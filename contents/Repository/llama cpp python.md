---
already_read: true
link: https://github.com/abetlen/llama-cpp-python
read_priority: 0
relevance: 5
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-07-17'
---

https://github.com/abetlen/llama-cpp-python
## Summary

llama-cpp-python provides Python bindings for the C++ library llama.cpp, enabling efficient inference for large language models (LLMs) like Llama. Key features include:

- **Installation**: Requires Python 3.8+, a C compiler (gcc/clang/Xcode/Visual Studio), and optional hardware acceleration backends (CUDA, Metal, OpenBLAS, ROCm, Vulkan, SYCL). Pre-built wheels are available for CPU/CUDA/Metal/ROCm/Vulkan.
- **High-level API**: Simplifies model interaction with OpenAI-like interfaces for text/chat completion, function calling, JSON mode, multi-modal models (e.g., LLaVA, Moondream), and embeddings. Supports models in GGUF format, including Hugging Face Hub downloads.
- **Low-level API**: Direct ctypes bindings to llama.cpp’s C API for advanced users.
- **Web Server**: OpenAI-compatible API server for local deployment (e.g., `python -m llama_cpp.server --model model.gguf`).
- **Hardware Acceleration**: Configurable via `CMAKE_ARGS` (e.g., `-DGGML_CUDA=on` for NVIDIA GPUs).
- **Multi-modal Support**: Handles image inputs for models like LLaVA or Moondream.
- **Speculative Decoding**: Improves generation speed with draft models.
- **Documentation**: Available at [llama-cpp-python.readthedocs.io](https://llama-cpp-python.readthedocs.io/en/latest).

**Use Cases**: Local LLM inference, OpenAI API replacement, LangChain/LlamaIndex integration, and edge deployment. MIT licensed.
## Links

- [llama.cpp Official Repository](https://github.com/ggerganov/llama.cpp) : The official repository for llama.cpp, the C++ library that provides the foundational inference engine for the Python bindings in `llama-cpp-python`. This repository contains detailed documentation, build instructions, and additional optimizations for various hardware backends like OpenBLAS, CUDA, Metal, and more.
- [llama.cpp Documentation on OpenBLAS](https://github.com/ggerganov/llama.cpp#openblas) : Documentation for using OpenBLAS with llama.cpp, which is relevant for optimizing CPU-based inference in `llama-cpp-python`. This link provides guidance on enabling BLAS acceleration for faster performance.
- [llama.cpp C API Reference (llama.h)](https://github.com/ggerganov/llama.cpp/blob/master/llama.h) : The C API header file for llama.cpp, which defines the low-level functions and structures used by the Python bindings in `llama-cpp-python`. This is essential for understanding the underlying API and its capabilities.
- [Hugging Face Hub - Moondream2 Model](https://huggingface.co/vikhyatk/moondream2) : A multi-modal model (text + vision) available on Hugging Face Hub, which is compatible with `llama-cpp-python`. This model demonstrates the vision API support provided by the library.
- [Hugging Face Hub - MiniCPM-V-2_6 Model](https://huggingface.co/openbmb/MiniCPM-V-2_6-gguf) : A multi-modal model available on Hugging Face Hub, compatible with `llama-cpp-python`. This model supports vision and text capabilities, showcasing the library's support for advanced AI tasks.
- [Hugging Face Hub - Gemma-4-E4B-it-GGUF Model](https://huggingface.co/unsloth/gemma-4-E4B-it-GGUF) : A text-based model available on Hugging Face Hub, compatible with `llama-cpp-python`. This model is an example of the library's compatibility with state-of-the-art language models.
- [Hugging Face Hub - Llava-v1.6-34B Model](https://huggingface.co/cjpais/llava-v1.6-34B-gguf) : A multi-modal model (text + vision) available on Hugging Face Hub, compatible with `llama-cpp-python`. This model demonstrates the library's support for large-scale vision-language tasks.
- [Python LangChain Integration Guide](https://python.langchain.com/docs/integrations/llms/llamacpp) : Documentation for integrating `llama-cpp-python` with LangChain, a popular framework for building AI-powered applications. This link highlights the library's compatibility with LangChain for advanced workflows.
- [Llama.cpp Python Bindings Low-Level API](https://llama-cpp-python.readthedocs.io/en/latest/api-reference/#low-level-api) : Documentation for the low-level API of `llama-cpp-python`, which provides direct access to the C API of llama.cpp via ctypes. This is useful for users who need fine-grained control over the inference process.
- [Llama.cpp Python Bindings High-Level API](https://llama-cpp-python.readthedocs.io/en/latest/api-reference/#high-level-api) : Documentation for the high-level API of `llama-cpp-python`, which provides a simple Python interface for text completion, chat completion, and other tasks. This is ideal for users who want to quickly integrate the library into their projects.

## Topics

![[topics/Library/llama cpp python]]

![[topics/Concept/GGUF]]

![[topics/Concept/Hardware Acceleration Backends]]

![[topics/Concept/Multi modal Models]]

![[topics/Concept/Function Calling]]

![[topics/Tool/llama cpp]]

![[topics/Concept/Speculative Decoding]]

![[topics/Concept/OpenAI Compatible API]]

![[topics/Concept/Embeddings]]