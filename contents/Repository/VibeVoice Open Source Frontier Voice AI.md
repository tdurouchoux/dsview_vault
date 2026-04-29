---
already_read: true
link: https://github.com/microsoft/VibeVoice
read_priority: 0
relevance: 4
source: Alliance
tags:
- Natural_Language_Processing
type: Content
upload_date: '2026-04-29'
---

https://github.com/microsoft/VibeVoice
## Summary

VibeVoice is Microsoft's open-source frontier voice AI framework, offering **Text-to-Speech (TTS)** and **Automatic Speech Recognition (ASR)** models. Key innovations include **continuous speech tokenizers (7.5 Hz frame rate)** and a **next-token diffusion framework** combining LLMs for context and diffusion heads for high-fidelity audio.

### **Models & Features**
1. **VibeVoice-ASR-7B**
   - **Long-form ASR**: Processes **60-minute audio in a single pass** (64K tokens), preserving speaker tracking and semantic coherence.
   - **Structured outputs**: Transcribes *Who (speaker), When (timestamps), What (content)* with **customizable hotwords** for domain-specific accuracy.
   - **Multilingual**: Supports **50+ languages**; finetuning code available.
   - **Efficiency**: vLLM inference supported for faster processing.

2. **VibeVoice-TTS-1.5B** *(Temporarily unavailable)*
   - **Long-form TTS**: Generates **90-minute speech** with **up to 4 distinct speakers**, maintaining natural turn-taking and emotional nuance.
   - **Multilingual**: Supports English, Chinese, and cross-lingual synthesis.

3. **VibeVoice-Realtime-0.5B**
   - **Real-time TTS**: Lightweight (0.5B params) with **~300ms latency**, streaming input, and **10-minute long-form generation**.
   - **Experimental speakers**: Multilingual (9 languages) and 11 English styles.

### **Technical Highlights**
- **Tokenizers**: Ultra-low frame rate (7.5 Hz) for efficiency.
- **Diffusion framework**: Combines LLM context understanding with acoustic fidelity.
- **Integration**: Available via **Hugging Face Transformers** and **vLLM** for ASR.

### **Risks & Limitations**
- Potential **biases/errors** inherited from base models (e.g., Qwen2.5).
- **Deepfake risks**: High-quality synthetic speech may enable misuse (fraud, disinformation).
- **Not for commercial use** without further testing.

### **Resources**
- **Docs**: [Project Page](https://microsoft.github.io/VibeVoice/)
- **Playground**: [ASR Demo](https://huggingface.co/spaces/microsoft/VibeVoice-ASR-Playground)
- **Code**: [GitHub](https://github.com/microsoft/VibeVoice) (MIT License).
## Links

- [VibeVoice Project Page](https://microsoft.github.io/VibeVoice) : The official project page for VibeVoice, providing detailed information, demos, and examples of the open-source Frontier Voice AI models, including ASR, TTS, and Realtime models.
- [VibeVoice-ASR on Hugging Face](https://huggingface.co/microsoft/VibeVoice-ASR) : The Hugging Face repository for VibeVoice-ASR, a unified speech-to-text model supporting long-form audio processing, multilingual capabilities, and structured transcriptions.
- [VibeVoice-Realtime-0.5B on Hugging Face](https://huggingface.co/microsoft/VibeVoice-Realtime-0.5B) : The Hugging Face repository for VibeVoice-Realtime-0.5B, a lightweight real-time text-to-speech model designed for streaming and robust long-form speech generation.
- [VibeVoice-ASR Colab Demo](https://colab.research.google.com/github/microsoft/VibeVoice/blob/main/demo/VibeVoice_colab.ipynb) : A Google Colab notebook demonstrating the usage of VibeVoice-ASR for long-form speech recognition, allowing users to try the model interactively.
- [VibeVoice ASR Technique Report (ArXiv)](https://arxiv.org/pdf/2601.18184) : The technical report for VibeVoice-ASR, detailing the methodology, innovations, and performance metrics of the model.

## Topics

![[topics/Model/VibeVoice ASR]]

![[topics/Model/VibeVoice TTS]]

![[topics/Model/VibeVoice Realtime 0 5B]]

![[topics/Concept/Continuous Speech Tokenizers]]

![[topics/Concept/Next Token Diffusion Framework]]

![[topics/Platform/Hugging Face]]

![[topics/Concept/Structured Transcription]]

![[topics/Concept/Customized Hotwords]]