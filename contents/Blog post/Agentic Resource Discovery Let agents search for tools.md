---
already_read: true
link: https://huggingface.co/blog/agentic-resource-discovery-launch
read_priority: 0
relevance: 5
source: Data Points
tags:
- Natural_Language_Processing
type: Content
upload_date: '2026-06-22'
---

https://huggingface.co/blog/agentic-resource-discovery-launch
## Summary

Agentic Resource Discovery (ARD) is a draft open specification developed by industry contributors (Microsoft, Google, GoDaddy, Hugging Face, etc.) to address the discovery problem in agentic AI systems. It provides a discovery layer for agents to dynamically find tools, skills, and other agents at runtime, rather than relying on pre-installed, static catalogs.

Key technical points:
- ARD defines a static manifest format (`ai-catalog.json`) for publishers to host capabilities and a dynamic registry API (`POST /search`) for live discovery.
- It separates discovery from execution, enabling intent-based search with richer signals like publisher identity, compliance attestations, and tags.
- Hugging Face has implemented ARD via the **Hugging Face Discover Tool**, which integrates with the Hugging Face Hub to provide search access to Skills, ML applications, and MCP Servers.
- The tool supports multiple media types (e.g., `application/ai-skill`, `application/mcp-server+json`) and transforms existing Hub resources into ARD-compliant catalog entries.
- ARD can be accessed via the Hugging Face CLI (`hf discover search`), REST API, or MCP Server.
- The specification emphasizes verification (e.g., publisher identity, tamper-proofing) as a critical step in the discovery process.
- Next steps include tighter integration with federation modes and Hub-side support for static `ai-catalog.json` manifests.

ARD aims to standardize how agents discover and connect to capabilities across the web, akin to DNS for AI agents. Publishers can host an `ai-catalog.json` file to make their capabilities discoverable and verifiable.
## Links

- [Agentic Resource Discovery Specification](https://agenticresourcediscovery.org/) : Official website for the Agentic Resource Discovery (ARD) specification, providing detailed information about the open standard for how AI agents discover and connect to capabilities across the web.
- [Hugging Face Discover Tool](https://github.com/huggingface/hf-discover) : GitHub repository for the Hugging Face Discover Tool, a reference implementation of the ARD specification that enables search access to skills, ML applications, and MCP servers.
- [Hugging Face CLI](https://github.com/huggingface/huggingface_hub) : GitHub repository for the Hugging Face CLI tool, which includes the `hf discover` command for searching ARD resources.
- [Agent Skills on the Hub](https://huggingface.co/docs/hub/agents-skills) : Documentation for Agent Skills on the Hugging Face Hub, explaining how to define and use agent-interactable skills within Spaces.
- [Hugging Face Spaces](https://huggingface.co/spaces) : Official page for Hugging Face Spaces, where users can host and discover interactive ML applications, including those compatible with ARD.

## Topics

![[topics/Concept/Agentic Resource Discovery ARD]]

![[topics/Concept/Model Context Protocol MCP]]

![[topics/Concept/A2A Agent to Agent Protocol]]

![[topics/Library/Hugging Face Discover Tool]]

![[topics/Platform/Hugging Face]]

![[topics/Concept/Federated Registries]]

![[topics/Tool/ai catalog json]]

![[topics/Concept/Agent Skills]]