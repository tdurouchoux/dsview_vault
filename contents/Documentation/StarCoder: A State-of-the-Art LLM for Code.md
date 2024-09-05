---
already_read: false
link: https://huggingface.co/blog/starcoder?utm_source=alphasignalai.beehiiv.com&utm_medium=newsletter&utm_campaign=is-this-the-end-of-regulation-free-ai
read_priority: 1
source: null
tags:
- Large_Language_Model
- Python
- Generative_AI
type: Content
upload_date: '2023-05-25'
---

https://huggingface.co/blog/starcoder?utm_source=alphasignalai.beehiiv.com&utm_medium=newsletter&utm_campaign=is-this-the-end-of-regulation-free-ai
## Summary

StarCoder and StarCoderBase are advanced Large Language Models (LLMs) for code, trained on a diverse dataset from GitHub, covering over 80 programming languages. StarCoder, a fine-tuned version of StarCoderBase, has approximately 15 billion parameters and was trained on 1 trillion tokens, specifically 35 billion Python tokens. It outperforms existing open-source code LLMs and competes with closed models like OpenAI's code-cushman-001.

Key features include:
- A context length exceeding 8,000 tokens, allowing for extensive input processing.
- Capabilities such as code autocompletion, modification based on instructions, and natural language explanations of code snippets.
- Enhanced safety measures, including a PII redaction pipeline and an attribution tracing tool, with a simplified OpenRAIL license for easier integration into products.

Evaluation results show StarCoder achieving a state-of-the-art score on the HumanEval benchmark, surpassing larger models. It also performs well in multilingual contexts and excels in data science benchmarks. Additionally, it can function as a tech assistant, leveraging its training on documentation and GitHub issues.

The training data was sourced from The Stack 1.2, ensuring permissive licensing and an opt-out process for contributors. The BigCode initiative, a collaboration between Hugging Face and ServiceNow, focuses on the responsible development of code LLMs.

Resources released alongside StarCoder include model weights, evaluation tools, and a PII dataset for training and evaluation.
## Links

1. [Paper](https://arxiv.org/abs/2305.06161) - A technical report about StarCoder detailing its architecture and performance.
2. [GitHub](https://github.com/bigcode-project/starcoder/tree/main) - Repository containing all the code for using or fine-tuning StarCoder.
3. [Tech Assistant Prompt](https://huggingface.co/datasets/bigcode/ta-prompt) - A prompt that enables StarCoder to function as a tech assistant for programming-related queries.
4. [StarCoder](https://huggingface.co/bigcode/starcoder) - The main page for StarCoder, providing access to the model and its features.
5. [StarCoderBase](https://huggingface.co/bigcode/starcoderbase) - The base model of StarCoder trained on a diverse set of programming languages.
## Topics

- [[topics/Model/StarCoder]]
- [[topics/Model/StarCoderBase]]
- [[topics/Concept/Tech Assistant Prompt]]
- [[topics/Library/StarCoder Chat]]
- [[topics/Library/StarCoder Playground]]