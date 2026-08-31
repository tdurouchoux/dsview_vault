---
already_read: false
link: https://alexzhang13.github.io/blog/2025/rlm/
read_priority: 5
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-09-01'
---

https://alexzhang13.github.io/blog/2025/rlm/

## Summary

Recursive Language Models (RLMs) introduce a novel inference strategy where LMs recursively interact with unbounded input context via REPL environments, significantly improving long-context performance and mitigating "context rot."

**Core Idea**
- RLMs enable LMs to decompose and recursively process input context as a variable in a REPL (e.g., Python notebook) environment.
- The root LM interacts with the context indirectly, avoiding direct exposure to its full length.

**Key Technical Details**
- **Environment**: Context is stored as a variable in a Python REPL, allowing the LM to peek, partition, grep, or launch recursive sub-queries.
- **Recursion**: The root LM (e.g., GPT-5-mini) can spawn recursive LM calls (depth=1) to handle sub-tasks, with outputs fed back into the environment.
- **Output**: Final answers are returned via `FINAL(...)` or `FINAL_VAR(...)` tags.

**Performance Highlights**
- **OOLONG Benchmark**: RLM(GPT-5-mini) outperforms GPT-5 by >34 points (~114% increase) on 132k-token contexts and by >15 points (~49% increase) on 263k-token contexts, while being cheaper per query.
- **BrowseComp-Plus**: RLM(GPT-5) maintains perfect performance on 1000 documents (~10M+ tokens), unlike baselines (GPT-5, ReAct + BM25) which degrade as context grows.
- **Context Rot Mitigation**: RLMs show no performance degradation with 10M+ tokens, unlike standard LMs.

**Advantages**
- Avoids context window clogging by never exposing the root LM to the full context.
- Flexible context interaction: peek, grep, partition, or summarize subsets programmatically.
- Scales test-time compute without requiring models trained on huge contexts.

**Limitations**
- Current implementation is unoptimized: recursive calls are blocking and lack prefix caching, leading to variable query times (seconds to minutes).
- No strong guarantees on controlling total API cost or runtime.

**Future Directions**
- Optimizing inference engines for asynchronous, cached recursive calls.
- Training LMs explicitly for recursive reasoning to further improve performance.
- Exploring deeper recursion (beyond depth=1) for more complex tasks.

**Code & Resources**
- Paper: [alphaxiv.org/abs/2512.24601](https://www.alphaxiv.org/abs/2512.24601)
- Official codebase: [github.com/alexzhang13/rlm](https://github.com/alexzhang13/rlm)
- Minimal implementation: [github.com/alexzhang13/rlm-minimal](https://github.com/alexzhang13/rlm-minimal)

## Links

- [Recursive Language Models (RLMs) - arXiv Paper](https://www.alphaxiv.org/abs/2512.24601) : The official arXiv preprint of the Recursive Language Models (RLMs) paper, detailing the methodology, experiments, and results of the proposed inference strategy for handling unbounded context lengths in language models.
- [Official RLM Codebase](https://github.com/alexzhang13/rlm) : The official GitHub repository for the Recursive Language Models (RLMs) implementation, providing code, examples, and documentation for building and experimenting with RLMs.
- [Minimal RLM Implementation](https://github.com/alexzhang13/rlm-minimal) : A minimal implementation of Recursive Language Models (RLMs) designed for quick adoption and experimentation, allowing users to build upon the core concepts with minimal setup.
- [BrowseComp-Plus Benchmark](https://openai.com/index/browsecomp/) : The BrowseComp-Plus benchmark, which evaluates agents on multi-hop, web-search queries with pre-downloaded documents, used in the RLM experiments to test handling of large contexts.
- [LoCoDiff Benchmark](https://abanteai.github.io/LoCoDiff-bench/) : The LoCoDiff benchmark, which evaluates language models on long-input, long-output tasks such as tracking git diff histories, demonstrating the capabilities of RLMs in programmatic contexts.


## Topics

![[topics/Library/REPL]]

![[topics/Dataset/BrowseComp Plus]]

![[topics/Library/BM25]]

![[topics/Model/GPT]]

![[topics/Concept/Recursive Language Models RLMs]]

![[topics/Platform/Oolong]]

![[topics/Concept/Context Rot]]