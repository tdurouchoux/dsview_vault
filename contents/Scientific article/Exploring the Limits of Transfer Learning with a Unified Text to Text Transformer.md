---
already_read: false
link: https://arxiv.org/pdf/1910.10683
read_priority: 5
relevance: 0
source: null
tags:
- Natural_Language_Processing
- Deep_Learning
type: Content
upload_date: '2025-02-20'
---

![](artefacts/1910.10683)
## Summary

The paper explores transfer learning in natural language processing (NLP) through a unified text-to-text framework, introducing the "Text-to-Text Transfer Transformer" (T5). Key points include:

- **Transfer Learning**: The study emphasizes the effectiveness of pre-training models on large datasets before fine-tuning on specific tasks, which has become a standard practice in NLP.

- **Text-to-Text Framework**: All NLP tasks are reformulated as text-to-text problems, allowing the same model and training procedure to be applied across various tasks, including translation, summarization, and classification.

- **Colossal Clean Crawled Corpus (C4)**: A new dataset created from the Common Crawl, which is cleaned and filtered to improve the quality of the text used for pre-training.

- **Model Architecture**: The paper primarily uses the Transformer architecture, comparing various configurations (encoder-decoder, shared parameters) and finding that the original architecture performs best.

- **Unsupervised Objectives**: Different denoising objectives were tested, with the span-corruption objective showing improved performance and efficiency.

- **Scaling**: The authors demonstrate that increasing model size and training duration leads to better performance, with the largest models (up to 11 billion parameters) achieving state-of-the-art results on multiple benchmarks.

- **Multi-task Learning**: The study investigates training on multiple tasks simultaneously, finding that while it can be beneficial, pre-training followed by fine-tuning generally yields better results.

- **Performance Results**: T5 models achieved state-of-the-art performance on 18 out of 24 tasks, including significant improvements on benchmarks like GLUE and SuperGLUE.

- **Future Directions**: The authors suggest further research into efficient knowledge extraction, language-agnostic models, and methods to improve performance on low-resource tasks.

The paper concludes by releasing the T5 models, code, and datasets to facilitate further research in the field.
## Topics

![](topics/Concept/Transfer%20Learning)

![](topics/Dataset/Colossal%20Clean%20Crawled%20Corpus%20C4)

![](topics/Model/Text%20to%20Text%20Transfer%20Transformer%20T5)

![](topics/Tool/TensorFlow%20Datasets)

![](topics/Concept/Multi%20task%20Learning)