---
type: Concept
---

A unified approach to natural language processing tasks where all tasks are formulated as text-to-text problems. This means the model takes text as input and produces text as output, allowing for a consistent training objective and decoding procedure across different tasks. The framework is instantiated by models like T5 (Text-to-Text Transfer Transformer), an encoder-decoder transformer introduced by Google in 2019, which frames all NLP tasks (e.g., text classification) as text-to-text problems and is pre-trained on a large corpus using span corruption.