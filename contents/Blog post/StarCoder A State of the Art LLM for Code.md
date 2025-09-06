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

StarCoder is a state-of-the-art Large Language Model (LLM) for code, developed by Hugging Face's BigCode collaboration. It is trained on permissively licensed data from GitHub, covering over 80 programming languages, Git commits, GitHub issues, and Jupyter notebooks. The model has ~15 billion parameters and was trained on 1 trillion tokens. StarCoderBase, the base model, was further fine-tuned on 35 billion Python tokens to create StarCoder.

Key features and achievements:
- Outperforms existing open Code LLMs and matches or surpasses closed models like OpenAI's code-cushman-001 on popular programming benchmarks.
- Context length of over 8,000 tokens, enabling a wide range of applications such as code autocompletion, modification, and explanation.
- Multilingual capabilities, excelling in benchmarks like MultiPL-E and DS-1000.
- Can act as a technical assistant with the right prompting.
- Released under an improved OpenRAIL license, promoting safe and responsible use.

Additional resources include model weights, data preprocessing and training code, evaluation harness, PII removal dataset, preprocessed dataset, and a code attribution tool. Tools and demos like StarCoder Chat, VSCode Extension, and StarCoder Playground are also available.
## Links

- [StarCoder Model](https://huggingface.co/bigcode/starcoder) : The StarCoder model page on Hugging Face, providing details and access to the model.
- [StarCoderBase Model](https://huggingface.co/bigcode/starcoderbase) : The StarCoderBase model page on Hugging Face, providing details and access to the base model.
- [StarCoder GitHub Repository](https://github.com/bigcode-project/starcoder/tree/main) : The GitHub repository for StarCoder, containing code, documentation, and resources for using and fine-tuning the model.
- [StarCoder Playground](https://huggingface.co/spaces/bigcode/bigcode-playground) : An interactive playground for experimenting with StarCoder.
- [StarCoder Editor](https://huggingface.co/spaces/bigcode/bigcode-editor) : An editor for using StarCoder to write and edit code.

## Topics

![](topics/Model/StarCoder)

![](topics/Model/StarCoderBase)

![](topics/Concept/Tech%20Assistant)

![](topics/Dataset/The%20Stack%201%202)

![](topics/Concept/Personal%20Identifiable%20Information%20PII%20Redaction)

![](topics/Concept/Code%20Attribution)

![](topics/Concept/OpenRAIL%20License)