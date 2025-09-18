---
already_read: false
link: https://huggingface.co/blog/starcoder
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2023-05-25'
---

https://huggingface.co/blog/starcoder
## Summary

StarCoder is a state-of-the-art Large Language Model (LLM) for code, developed by Hugging Face's BigCode collaboration. It is trained on permissively licensed data from GitHub, covering over 80 programming languages, Git commits, issues, and Jupyter notebooks. The model has ~15B parameters and was trained on 1 trillion tokens. StarCoderBase, the base model, was further fine-tuned on 35B Python tokens to create StarCoder.

Key features and findings:
- StarCoder outperforms existing open Code LLMs and matches or surpasses closed models like OpenAI's code-cushman-001 on popular programming benchmarks.
- It has a context length of over 8,000 tokens, enabling a wide range of applications such as code autocompletion, modification, and explanation.
- StarCoder is multilingual and performs well on benchmarks like MultiPL-E and DS-1000.
- It can act as a technical assistant when prompted appropriately.
- The model was trained on a subset of The Stack 1.2, with Personal Identifiable Information (PII) removed.

Additional releases include model weights, data preprocessing and training code, evaluation harness, PII dataset, preprocessed dataset, and a code attribution tool. StarCoder is licensed under the BigCode OpenRAIL-M v1 license agreement.

Links to resources and tools are provided, including model weights, evaluation harness, PII dataset, preprocessed dataset, and code attribution tool. The model is available for use and fine-tuning, with resources and links available at huggingface.co/bigcode.
## Links

- [StarCoder Model](https://huggingface.co/bigcode/starcoder) : The StarCoder model page on Hugging Face, providing details and access to the StarCoder model.
- [StarCoderBase Model](https://huggingface.co/bigcode/starcoderbase) : The StarCoderBase model page on Hugging Face, providing details and access to the StarCoderBase model.
- [StarCoder GitHub Repository](https://github.com/bigcode-project/starcoder/tree/main) : The GitHub repository for StarCoder, containing code, data preprocessing, and training information.
- [StarCoder Technical Report](https://arxiv.org/abs/2305.06161) : The technical report about StarCoder, providing in-depth information about the model and its development.
- [StarCoder Playground](https://huggingface.co/spaces/bigcode/bigcode-playground) : An interactive playground to experiment with StarCoder.

## Topics

![[topics/Concept/MultiPL E]]

![[topics/Concept/HumanEval]]

![[topics/Concept/Code Attribution]]

![[topics/Concept/Tech Assistant Prompt]]

![[topics/Concept/DS 1000]]

![[topics/Model/StarCoderBase]]

![[topics/Dataset/The Stack 1 2]]

![[topics/Concept/Personal Identifiable Information PII Redaction]]

![[topics/Concept/OpenRAIL License]]

![[topics/Model/StarCoder]]