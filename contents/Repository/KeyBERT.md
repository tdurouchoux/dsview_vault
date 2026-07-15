---
already_read: true
link: https://maartengr.github.io/KeyBERT/
read_priority: 0
relevance: 4
source: null
tags:
- Natural_Language_Processing
type: Content
upload_date: '2026-07-15'
---

https://maartengr.github.io/KeyBERT/
## Summary

KeyBERT is a lightweight keyword extraction tool that uses BERT embeddings and cosine similarity to identify the most relevant words/phrases in a document. It works by:

1. Generating document embeddings with BERT
2. Extracting N-gram word/phrase embeddings
3. Ranking them by cosine similarity to the document

Key features:
- No training required (uses pre-trained models)
- Supports customizable N-gram ranges (e.g., single words or phrases)
- Minimal setup (pip install + 3 lines of code)
- Works with multiple documents for batch processing

Installation: `pip install keybert` (with optional backends like Flair, SpaCy, etc.)

Example usage:
```python
from keybert import KeyBERT
kw_model = KeyBERT()
keywords = kw_model.extract_keywords(doc, keyphrase_ngram_range=(1,2))
```

The tool is designed for simplicity while leveraging powerful BERT embeddings for semantic keyword extraction.
## Links

- [KeyBERT on PyPI](https://pypi.org/project/keybert/) : Official PyPI page for KeyBERT, providing installation instructions and package details.
- [KeyBERT GitHub Repository](https://github.com/MaartenGr/keyBERT) : The official GitHub repository for KeyBERT, containing the source code, additional documentation, and community contributions.
- [RAKE GitHub Repository](https://github.com/aneesha/RAKE) : GitHub repository for RAKE, a traditional keyword extraction algorithm mentioned for comparison.
- [YAKE GitHub Repository](https://github.com/LIAAD/yake) : GitHub repository for YAKE, another traditional keyword extraction algorithm mentioned for comparison.

## Topics

![[topics/Library/KeyBERT]]

![[topics/Concept/Keyword Extraction]]

![[topics/Concept/N gram Range]]

![[topics/Model/BERT]]

![[topics/Concept/Cosine Similarity]]

![[topics/Concept/Embeddings]]