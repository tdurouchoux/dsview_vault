---
already_read: false
link: https://huggingface.co/blog/starcoder
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2023-05-25'
---

https://huggingface.co/blog/starcoder
## Summary

StarCoder and StarCoderBase are advanced Large Language Models (LLMs) for code developed by Hugging Face, trained on diverse, permissively licensed data from GitHub across 80+ programming languages. StarCoder uses approximately 15 billion parameters and has been fine-tuned on 35 billion Python tokens to achieve superior performance on coding benchmarks.

Key highlights include:
- Strong performance against notable models: StarCoder surpasses both open-source Code LLMs and closed models such as OpenAI's code-cushman-001, achieving over 40% on the HumanEval benchmark with effective prompting techniques.
- Multilingual capabilities with robust performance across multiple languages, surpassing competitors on specific benchmarks like DS-1000.
- Application as a technical assistant by leveraging its trained documentation and issue datasets, showing potential in answering programming queries.
- Enhanced safety features, including improved PII redaction and a novel attribution tracing tool for ethics in machine learning.
- Public availability under an OpenRAIL license to facilitate easy integration into products.

Additional resources accompany the model, including complete datasets, evaluation tools, and prompts to utilize StarCoder effectively in different coding contexts.
## Links

- [StarCoder at Hugging Face](https://huggingface.co/bigcode/starcoder) : Official page for StarCoder, detailing its features and access.
- [StarCoderBase Model](https://huggingface.co/bigcode/starcoderbase) : Information about the StarCoderBase model that was further trained on Python.
- [StarCoder Code Search](https://huggingface.co/spaces/bigcode/search) : Space for performing full-text search on the code in the StarCoder pretraining dataset.
- [StarCoder Playground](https://huggingface.co/spaces/bigcode/bigcode-playground) : Interactive platform to experiment with the functionalities of StarCoder.
- [StarCoder Data](https://huggingface.co/datasets/bigcode/starcoderdata) : Access to the training data used for the StarCoder model.

## Topics

![](topics/Model/StarCoder)

![](topics/Model/StarCoderBase)

![](topics/Dataset/The%20Stack%201%202)

![](topics/Concept/Technical%20Assistant%20Prompting)

![](topics/Platform/Hugging%20Face)

![](topics/Tool/StarCoder%20Chat)

![](topics/Tool/StarCoder%20Playground)