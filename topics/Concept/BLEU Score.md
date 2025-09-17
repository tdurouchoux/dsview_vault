---
type: Concept
---

The BLEU (Bilingual Evaluation Understudy) score is a reference-based metric used to evaluate the quality of machine-translated text. It measures the precision of the generated text by comparing it to one or more reference translations. The BLEU score calculates the fraction of n-grams (contiguous sequences of n items from a sample of text) in the candidate text that appear in the reference text. The score is typically calculated for individual segments (such as sentences) and then averaged over the entire corpus. The BLEU score does not take into account punctuation or grammatical correctness, and a perfect score indicates that the candidate text is identical to one of the reference translations.