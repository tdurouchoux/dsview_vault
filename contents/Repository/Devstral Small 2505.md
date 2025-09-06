---
already_read: true
link: https://huggingface.co/mistralai/Devstral-Small-2505
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2025-05-30'
---

https://huggingface.co/mistralai/Devstral-Small-2505
## Summary

Devstral Small 1.0 is an agentic LLM designed for software engineering tasks, developed collaboratively by Mistral AI and All Hands AI. Key features include:

- **Agentic Coding**: Excels at agentic coding tasks, making it ideal for software engineering agents.
- **Lightweight**: Compact size of 24 billion parameters, suitable for local deployment on a single RTX 4090 or a Mac with 32GB RAM.
- **Apache 2.0 License**: Open license for both commercial and non-commercial use.
- **Context Window**: 128k context window.
- **Tokenizer**: Uses a Tekken tokenizer with a 131k vocabulary size.

**Benchmark Results**:
- Achieves a score of 46.8% on SWE-Bench Verified, outperforming prior open-source models by 6%.

**Usage**:
- Recommended to use with the OpenHands scaffold.
- Can be used via API or locally with libraries like vLLM, Mistral-inference, Transformers, LMStudio, llama.cpp, and Ollama.

**Example Use Case**:
- Building a To-Do list app with FastAPI and React, demonstrating the model's ability to generate and iterate on code.

**Model Details**:
- Finetuned from Mistral-Small-3.1, with the vision encoder removed.
- Model size: 23.6B params, tensor type: BF16.

**Inference Providers**:
- Not currently deployed by any Inference Provider.

**Related Models**:
- Base model: Mistral-Small-3.1-24B-Base-2503.
- Finetuned from Mistral-Small-3.1-24B-Instruct-2503.
- 12 finetunes, 3 merges, and 42 quantizations available.
## Links

- [All Hands AI](https://www.all-hands.dev/) : All Hands AI is a company that specializes in AI-powered software engineering tools and solutions. Their website provides information about their products, services, and team.
- [Mistral AI](https://mistral.ai/) : Mistral AI is a company that develops large language models. Their website provides information about their models, including Devstral, and their team.

## Topics

![](topics/Model/Devstral%20Small%201%200)

![](topics/Library/OpenHands)

![](topics/Library/Mistral%20inference)

![](topics/Library/LMStudio)

![](topics/Library/llama%20cpp)

![](topics/Concept/Agentic%20Coding)

![](topics/Dataset/SWE%20Bench)

![](topics/Library/vLLM)

![](topics/Concept/Ollama)