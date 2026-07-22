---
already_read: true
link: https://www.langchain.com/blog/introducing-openwiki-an-open-source-agent-for-repo-documentation
read_priority: 0
relevance: 4
source: null
tags:
- Development_tool
type: Content
upload_date: '2026-07-22'
---

https://www.langchain.com/blog/introducing-openwiki-an-open-source-agent-for-repo-documentation
## Summary

OpenWiki is an open-source agent and CLI tool for automatically generating and maintaining documentation for codebases. It creates a structured wiki that helps coding agents understand repo context (e.g., key logic, file connections) without manual updates. Key features:

- **Automated Wiki Generation**: Uses models (e.g., OpenRouter, OpenAI) to create and update docs.
- **Integration**: Updates agent instruction files (e.g., AGENTS.md) with wiki references for seamless agent retrieval.
- **GitHub Action**: Runs scheduled updates based on code changes (via `git diff`).
- **Tracing**: Supports LangSmith for debugging agent interactions with the wiki.

**Getting Started**:
```bash
npm install -g openwiki
openwiki --init  # Configures model provider and generates docs
```
OpenWiki is built on DeepAgents and prioritizes scalability for large repos. Future use cases may extend beyond codebases. [GitHub repo](https://github.com/langchain-ai/openwiki).
## Links

- [OpenWiki GitHub Repository](https://github.com/langchain-ai/openwiki) : The official GitHub repository for OpenWiki, an open-source agent and CLI tool designed to generate and maintain documentation for codebases.
- [DeepWiki](https://deepwiki.com/) : A tool inspired by OpenWiki, providing structured documentation for codebases to help agents understand repository context.
- [LangChain DeepAgents Documentation](https://docs.langchain.com/oss/python/deepagents/overview) : Documentation for DeepAgents, the framework underlying OpenWiki, which supports tracing and agent infrastructure.
- [LangSmith Platform](https://langsmith.com/) : The platform where OpenWiki traces its runs for debugging, observability, and evaluation of agent-generated documentation.

## Topics

![[topics/Tool/OpenWiki]]

![[topics/Library/DeepAgents]]

![[topics/Platform/LangSmith]]

![[topics/Concept/Agent Instruction Files AGENTS md]]

![[topics/Concept/GitHub Action for Documentation Updates]]