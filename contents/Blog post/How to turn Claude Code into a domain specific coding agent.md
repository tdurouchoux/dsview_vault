---
already_read: true
link: https://blog.langchain.com/how-to-turn-claude-code-into-a-domain-specific-coding-agent/
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- AI_agent
- Development_tool
type: Content
upload_date: '2025-10-04'
---

https://blog.langchain.com/how-to-turn-claude-code-into-a-domain-specific-coding-agent/
## Summary

The content discusses how to transform Claude Code into a domain-specific coding agent, focusing on improving performance with custom libraries, new library versions, internal APIs, or niche frameworks. The authors, developers of LangGraph and LangChain, experimented with various context engineering techniques and share their findings.

Key points include:

1. **Context Engineering Techniques**:
   - Raw documentation access was less effective and filled the context window quickly.
   - A concise, structured guide (Claude.md) outperformed simple documentation tools.
   - Combining base knowledge (Claude.md) with detailed documentation access yielded the best results.

2. **Claude Code Configurations Tested**:
   - Claude Vanilla: Out-of-the-box Claude Code.
   - Claude + MCP: Claude Code connected to an MCP server for documentation access.
   - Claude + Claude.md: Claude Code with a detailed Claude.md file.
   - Claude + MCP + Claude.md: Claude with access to both Claude.md and MCP server.

3. **Tools and Guides**:
   - **MCP Tool**: An open-source MCP server providing documentation access via tools like list_doc_sources and fetch_docs.
   - **Claude.md**: A condensed guide for LangGraph, including instructions, sample code, common pitfalls, and anti-patterns.

4. **Evaluation Framework**:
   - **Smoke Tests**: Verify basic functionality like code compilation and expected input/output handling.
   - **Task Requirement Tests**: Validate task-specific functionality.
   - **Code Quality & Implementation Evaluation**: Use LLM-as-a-Judge to assess code quality, design choices, and adherence to best practices.

5. **Results**:
   - Claude + Claude.md outperformed Claude + MCP.
   - Claude + Claude.md + MCP used documentation more effectively and achieved the best results.
   - MCP tools improved scores by ~10 percentage points but were less effective than Claude.md for task completion and code quality.

6. **Key Takeaways**:
   - Avoid context overload by using smarter retrieval tooling.
   - Claude.md has the highest payoff and is easier to set up than MCP servers.
   - Write good instructions highlighting core concepts, unique functionality, and common primitives.
   - Combining Claude.md with MCP tools yields the best results for domain-specific libraries.

The appendix includes detailed results for three specific tasks: Text-to-SQL Agent, Company Researcher, and Categories of Memories, showcasing performance differences across Claude Code configurations and categories.
## Links

- [Claude.md](http://claude.md/?ref=blog.langchain.com) : Claude.md is a documentation tool used to provide condensed and structured guidance for coding agents, specifically for domain-specific libraries like LangGraph. It includes detailed instructions, common pitfalls, and anti-patterns to help agents write better code.
- [LangChain Documentation](https://python.langchain.com/docs/get_started/introduction) : The LangChain documentation provides an introduction to LangChain, a framework for developing applications powered by language models. It includes guides, API references, and examples to help developers get started with LangChain.
- [MCPDoc Server](https://github.com/langchain-ai/mcpdoc?ref=blog.langchain.com) : The MCPDoc server is an open-source tool that provides access to library documentation for coding agents. It exposes tools like list_doc_sources and fetch_docs to help agents retrieve specific documentation as needed.

## Topics

![[topics/Concept/MCPDoc Server]]

![[topics/Concept/Claude md]]

![[topics/Concept/Context Engineering]]

![[topics/Concept/LangGraph]]

![[topics/Library/LangChain]]