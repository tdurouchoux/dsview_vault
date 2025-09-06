---
type: Concept
---

BERTScore is an evaluation metric for text generation tasks, such as summarization and translation. It leverages the contextual embeddings from pre-trained language models like BERT to compute the similarity between the candidate and reference sentences. Unlike traditional metrics that rely on exact word matches, BERTScore captures semantic similarity by comparing the contextual embeddings of words in the candidate and reference texts. This approach allows BERTScore to better align with human judgments of text quality, particularly in tasks where the generated text may paraphrase the reference text rather than copying it verbatim.