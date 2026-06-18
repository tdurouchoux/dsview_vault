---
already_read: true
link: https://openrouter.ai/blog/announcements/fusion-beats-frontier/
read_priority: 0
relevance: 3
source: Data Points
tags:
- Large_Language_Model
type: Content
upload_date: '2026-06-18'
---

https://openrouter.ai/blog/announcements/fusion-beats-frontier/
## Summary

OpenRouter introduces **Fusion**, a tool that synthesizes outputs from multiple models to outperform individual models in deep research tasks. Key findings:

- **Panels of models consistently outperform solo models**: E.g., Fable 5 + GPT-5.5 scored 69.0% vs. Fable 5 alone at 65.3% on DRACO benchmark.
- **Budget panels can rival frontier models**: A panel of budget models (Gemini 3 Flash, Kimi K2.6, DeepSeek V4 Pro) nearly matched Fable 5’s score at 50% lower cost.
- **Fusion works via one API call**: Dispatches prompts to a panel of models in parallel, with a judge model synthesizing the best output.
- **DRACO benchmark tests reasoning, tool use, and synthesis**: Evaluates factual accuracy, breadth/depth, presentation, and citation quality.
- **Preventing cheating**: Excluded benchmark rubric sources from web search to avoid contamination.
- **Fusing a model with itself boosts performance**: Opus 4.8 + itself scored 65.5% vs. 58.8% solo, highlighting synthesis benefits.
- **Four ways to use Fusion**: Chatroom, model slug, server tool, or plugin.

Fusion is not a drop-in replacement for all tasks (e.g., coding) but excels in complex research. Performance gains come from diversity and synthesis, not just model choice.
## Links

- [DRACO Benchmark by Perplexity AI](https://www.perplexity.ai/) : The DRACO benchmark, developed by Perplexity AI, is a deep research benchmark used to evaluate the performance of models like Fusion. It tests reasoning, tool usage, and knowledge synthesis across 100 tasks spanning 10 domains. This link points to Perplexity AI, the creator of the DRACO benchmark, which is central to the evaluation methodology discussed in the content.
- [Fusion Router Documentation](https://openrouter.ai/docs/guides/routing/routers/fusion-router) : This link leads to the official documentation for the Fusion Router feature on OpenRouter. It explains how Fusion works as a routing mechanism to combine the outputs of multiple models into a single, optimized response. This is highly relevant as it directly relates to the core functionality of Fusion described in the content.
- [Fusion Server Tools Documentation](https://openrouter.ai/docs/guides/features/server-tools/fusion) : This link provides detailed documentation on the Fusion server tools offered by OpenRouter. It explains how Fusion integrates with server tools like web search and web fetch to synthesize responses from multiple models. This is critical for understanding the technical implementation of Fusion.
- [Exa.ai](https://exa.ai) : Exa.ai is the provider of the web search and fetch tools used by Fusion to gather real-time information from the web. This is a key component of the deep research tasks evaluated in the content, making Exa.ai highly relevant for understanding Fusion's functionality.

## Topics

![[topics/Concept/Model Fusion]]

![[topics/Concept/Data Contamination]]

![[topics/Dataset/DRACO Benchmark]]

![[topics/Tool/Web Search and Fetch Tools]]

![[topics/Concept/Judge Model LLM as a Judge]]

![[topics/Platform/OpenRouter]]