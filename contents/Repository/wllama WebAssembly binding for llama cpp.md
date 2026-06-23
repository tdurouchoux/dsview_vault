---
already_read: true
link: https://github.com/ngxson/wllama
read_priority: 0
relevance: 5
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-06-23'
---

https://github.com/ngxson/wllama
## Summary

wllama is a WebAssembly binding for llama.cpp, enabling on-browser LLM inference. Key features include an OpenAI-compatible API, WebGPU support, multimodal (image/audio) and tool-calling support, and direct browser-based inference without backend/GPU requirements. It supports quantized models (Q4/Q5/Q6) and auto-switches between single/multi-thread builds. Limitations include 2GB file size cap (workaround via model splitting) and need for specific headers for multi-threading. Pre-built npm package available. Demo apps and docs provided. Compilation from source possible via Docker.
## Links

- [wllama WebGPU Support PR](https://github.com/ngxson/wllama/pull/215) : This link points to the pull request that introduced WebGPU support in wllama, which is a significant feature for enabling GPU acceleration in browser-based LLM inference.
- [llama.cpp Releases](https://github.com/ggerganov/llama.cpp/releases) : This link provides access to the releases of llama.cpp, the backend library that wllama is built upon. It is essential for understanding compatibility and obtaining the latest updates or quantized models.
- [huggingface.co/spaces/ngxson/wllama](https://huggingface.co/spaces/ngxson/wllama) : This link leads to a Hugging Face Space demonstrating wllama in action. It is valuable for seeing a live example of the library's capabilities in a real-world scenario.
- [Reese Levine's WebGPU for llama.cpp Documentation](https://reeselevine.github.io/llamas-on-the-web/) : This link provides detailed documentation about WebGPU support in llama.cpp, authored by Reese Levine. It is highly relevant for understanding the technical implementation and performance considerations of WebGPU in wllama.
- [npm Package for wllama](https://www.npmjs.com/package/@wllama/wllama) : This link directs to the npm package for wllama, which is the pre-built library that users can install and integrate into their projects. It is crucial for developers looking to adopt wllama in their workflows.

## Topics

![[topics/Concept/WebAssembly WASM]]

![[topics/Concept/WebGPU]]

![[topics/Tool/GGUF]]

![[topics/Platform/Hugging Face]]

![[topics/Concept/Multimodality]]

![[topics/Concept/Function Calling Tool Calling]]

![[topics/Tool/llama cpp]]

![[topics/Concept/Quantization]]