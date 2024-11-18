---
already_read: false
link: https://huggingface.co/blog/starcoder?utm_source=alphasignalai.beehiiv.com&utm_medium=newsletter&utm_campaign=is-this-the-end-of-regulation-free-ai
read_priority: 1
source: null
tags:
- Large_Language_Model
- Python
- Data_Quality
type: Content
upload_date: '2023-05-25'
---

https://huggingface.co/blog/starcoder?utm_source=alphasignalai.beehiiv.com&utm_medium=newsletter&utm_campaign=is-this-the-end-of-regulation-free-ai
## Summary

StarCoder and StarCoderBase are advanced Large Language Models (LLMs) for code, trained on a diverse dataset from GitHub, covering over 80 programming languages. StarCoder, a fine-tuned version of StarCoderBase, has approximately 15 billion parameters and was trained on 1 trillion tokens, specifically optimized for Python with 35 billion tokens. It outperforms existing open-source code LLMs and competes with proprietary models like OpenAI's Codex.

Key features include:
- A context length exceeding 8,000 tokens, allowing for extensive input processing.
- Capabilities such as code autocompletion, modification based on instructions, and natural language explanations of code snippets.
- Enhanced safety measures, including a PII redaction pipeline and an attribution tracing tool, with a simplified OpenRAIL license for easier integration into products.

Evaluation results show StarCoder achieving state-of-the-art performance on benchmarks like HumanEval, with a score improvement from 34% to over 40% through specific prompting techniques. It also excels in multilingual coding tasks and outperforms other models in data science benchmarks.

StarCoder can function as a tech assistant, leveraging its training on documentation and GitHub issues. The training data was carefully curated to exclude personal identifiable information, and the project is part of the BigCode initiative, promoting responsible development of code LLMs.

Additional resources include model weights, evaluation tools, and a PII dataset, all available under appropriate licenses.
## Links

1. [StarCoder](https://huggingface.co/bigcode/starcoder) - The main page for StarCoder, a state-of-the-art LLM for code, detailing its capabilities and features.
2. [StarCoderBase](https://huggingface.co/bigcode/starcoderbase) - Information about StarCoderBase, the foundational model trained on 80+ programming languages.
3. [StarCoder Chat](https://huggingface.co/chat?model=bigcode/starcoder) - A platform to interact with StarCoder through chat, showcasing its tech assistant capabilities.
4. [StarCoder License Agreement](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) - Details on the licensing terms for using StarCoder, important for developers and companies.
5. [GitHub Repository](https://github.com/bigcode-project/starcoder/tree/main) - The GitHub repository for StarCoder, containing code and resources for using or fine-tuning the model.
## Topics

![](topics/Model/StarCoder)

![](topics/Model/StarCoderBase)

![](topics/Dataset/The%20Stack%201%202)

![](topics/Product/StarCoder%20Chat)

![](topics/Product/VSCode%20Extension)