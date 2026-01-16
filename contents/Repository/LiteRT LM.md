---
already_read: true
link: https://github.com/google-ai-edge/LiteRT-LM
read_priority: 0
relevance: 4
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2026-01-17'
---

https://github.com/google-ai-edge/LiteRT-LM
## Summary

LiteRT-LM is a C++ library designed for efficiently running language models across various edge platforms. It builds on LiteRT and provides a pipeline framework for deploying and running LLMs, including support for cross-platform deployment, hardware acceleration, and flexible customization.

Key features include:
- C++ API for efficient language model execution
- Cross-platform support via portable C++
- Flexibility for customization
- Hardware acceleration for optimal device performance

The library supports multiple platforms (Android, macOS, Windows, Linux, Embedded) with varying backend support (CPU, GPU, NPU). It also supports several models like Gemma3-1B, Gemma-3n-E2B, Gemma-3n-E4B, phi-4-mini, qwen2.5-1.5b, and FunctionGemma-270M.

The repository includes detailed instructions for building and running the demo, with specific steps for different platforms. The LiteRT-LM API is designed around two primary classes: Engine and Session, providing functionalities for text generation, performance benchmarking, and both synchronous and asynchronous execution modes.

The library also supports multimodal data input, including text, image, and audio, and provides advanced control over the prefill and decode phases of transformer inference.

LiteRT-LM is part of the Google AI Edge stack, building on LiteRT and complementing MediaPipe GenAI Tasks. It uses the .litertlm format, an evolution of the .task file format, for better compression and additional metadata.

For reporting issues or contributing, users are encouraged to use the GitHub Issues page, providing clear titles and detailed descriptions. The repository is licensed under Apache-2.0 and has seen contributions from 24 contributors, with the primary language being C++.
## Links

- [LiteRT-LM GitHub Releases](https://github.com/google-ai-edge/LiteRT-LM/releases/latest) : Latest releases of LiteRT-LM, including pre-built binaries for various platforms.
- [LiteRT-LM Documentation](https://ai.google.dev/edge/litert) : Official documentation for LiteRT-LM, providing detailed information on how to use the library.
- [LiteRT-LM Hugging Face Models](https://huggingface.co/litert-community) : Hugging Face community page for LiteRT-LM models, including download links and model details.

## Topics

![[topics/Concept/Neural Processing Units NPUs]]

![[topics/Concept/Function Calling]]

![[topics/Concept/Multi Modality Support]]

![[topics/Tool/LiteRT LM]]