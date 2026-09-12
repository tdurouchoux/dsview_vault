---
already_read: true
link: https://declaude.org/watermarking/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Natural_Language_Processing
type: Content
upload_date: '2026-09-12'
---

https://declaude.org/watermarking/

## Summary

AI text watermarking embeds invisible, copy-resistant markers in AI-generated text by subtly biasing word choices, enabling detection by the key-holder.

**Core concept**
- Watermarks exist in word-choice patterns, not characters or metadata.
- Models generate text by probabilistically selecting from shortlists of valid next words.

**Watermarking mechanism**
- A secret key splits candidate words into "green" (favored) and "red" at each decision point.
- The model’s word-selection probabilities are gently tilted toward green words.
- Coloring depends on preceding context, so the same word may be green or red in different positions.
- Alternative schemes (SynthID, Aaronson’s) achieve the same effect via tournaments or key-derived dice rolls.

**Detection**
- The key-holder recolors the text and counts green-word frequency; marked text exceeds chance (~50%).
- Detection strength scales with text length (e.g., 1,500 words at ~55% green may flag).
- Short or highly constrained text (code, facts) carries weak or no mark.

**Editing impact**
- Marks survive only in untouched word runs; edits break context windows, erasing local evidence.
- Light paraphrasing dilutes but may not fully remove marks; full meaning-based rewrites erase them.
- Open-model tests show ~0.5% window survival after full rewrites, reducing detection to chance.
- Context-free (unigram) marks resist rewrites but risk reverse-engineering.

**Practical implications**
- Detection is private (requires provider’s key) and probabilistic, not a stylistic "AI detector."
- A mark indicates *processing* by the model, not authorship (e.g., human text edited by AI may be marked).
- Providers (Google, Anthropic) implement or plan detection tooling, but details are often undisclosed.
- No public method reliably detects Claude’s production watermark yet.

## Links

- [How Claude marks AI-generated content](https://support.claude.com/en/articles/16266773-how-claude-marks-ai-generated-content) : Official documentation from Anthropic explaining how Claude's text watermarking works, including the technical details of the watermarking scheme and its implications for detection.


## Topics

![[topics/Model/Claude]]

![[topics/Library/MarkLLM]]

![[topics/Concept/AI text watermarking]]

![[topics/Concept/KGW scheme]]

![[topics/Concept/EXP scheme]]

![[topics/Concept/SynthID]]

![[topics/Dataset/ICML 2023]]

![[topics/Dataset/Nature 2024]]

![[topics/Model/Gemini]]