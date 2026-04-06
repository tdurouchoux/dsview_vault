---
already_read: false
link: https://bettercodebetterscience.github.io/book/ai-coding-assistants/
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2026-04-04'
---

https://bettercodebetterscience.github.io/book/ai-coding-assistants/
## Summary

The content discusses the transformative impact of AI, particularly large language models (LLMs), on coding and scientific research. Key points include:

- **AI Coding Tools**: Tools like GitHub Copilot and ChatGPT have significantly reduced reliance on platforms like Stack Overflow, with AI coding capabilities improving exponentially since 2024.
- **Concerns with LLMs**: Issues include bias, copyright concerns, resource usage, and hallucinations (generating inaccurate information).
- **Agentic AI**: A new paradigm enabling LLMs to use external tools autonomously, enhancing coding efficiency but introducing new failure modes like going down rabbit holes.
- **AI Interaction Patterns**: Includes single-turn generation, context-aware code completion, programmatic access, and autonomous execution.
- **Principles for AI Coding Tools**: Emphasizes verification (testing generated code), context management (keeping context relevant and concise), and the importance of domain expertise.
- **Problem Decomposition**: AI models struggle with decomposing complex problems, requiring human expertise for architecture and design.
- **Failure Modes**: Taxonomy includes correctness failures, testing failures, feasibility failures, persistence failures, scope failures, security failures, instruction violations, and communication failures.
- **Code Smells in AI-Generated Code**: Specific issues like silent error swallowing, overly complex code, remnants of previous iterations, and inappropriate pattern imitation.
- **Version Control**: Strategies like creating branches before major tasks, commit-clear-reload cycles, and careful management of context and tasks.
- **Refactoring and Translation**: AI tools can assist in refactoring and translating code, but the quality of the original code impacts effectiveness.
- **Ten Simple Tips for AI-Assisted Scientific Programming**: Includes gathering domain knowledge, distinguishing problem framing from coding, choosing appropriate AI interaction models, and critically reviewing generated code.
- **Conclusion**: AI tools enhance productivity but do not replace programming expertise. Scientists must ensure the validity and correctness of AI-generated code, especially when publishing results.
## Links

- [Model Context Protocol (MCP) Documentation](https://modelcontextprotocol.io/docs/getting-started/intro) : Official documentation for the Model Context Protocol (MCP), a standard protocol for tool calling in AI agents. This is highly relevant as the content extensively discusses MCP and its role in enabling agentic AI for coding tasks.
- [METR AI Benchmark](https://metr.org/) : The METR website provides benchmarks for measuring the ability of AI models to complete long tasks. This is directly relevant to the content's discussion on quantifying the growth of AI coding tools and their performance.
- [Context Window Depletion Research](https://claudelog.com/mechanics/context-window-depletion/) : Research on context window depletion in AI models, which is directly related to the content's discussion on context management and the challenges of maintaining performance as context grows.
- [Chain-of-Thought Prompting Research Paper](https://arxiv.org/abs/2201.11903) : A research paper on chain-of-thought prompting, a technique mentioned in the content for encouraging deeper reasoning in AI models. This is relevant to the section on prompting strategies and improving AI problem-solving.
- [Ten Simple Rules for AI-Assisted Coding in Science](https://arxiv.org/abs/2510.22254) : A research paper titled 'Ten Simple Rules for AI-Assisted Coding in Science,' which aligns with the content's focus on best practices for using AI coding tools in scientific research.

## Topics

![[topics/Concept/AI Coding Agents]]

![[topics/Concept/Context Engineering and Management]]

![[topics/Concept/Hallucination in Language Models]]

![[topics/Concept/Test Driven Development TDD]]

![[topics/Concept/In Context Learning]]

![[topics/Concept/Code Smells in AI Generated Code]]

![[topics/Concept/Agentic AI vs Generative AI]]

![[topics/Concept/Model Context Protocol MCP]]

![[topics/Concept/Vibe Coding]]