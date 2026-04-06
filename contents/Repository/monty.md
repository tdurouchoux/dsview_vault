---
already_read: true
link: https://github.com/pydantic/monty
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2026-03-23'
---

https://github.com/pydantic/monty
## Summary

Monty is a minimal, secure Python interpreter written in Rust, designed for AI agents to safely execute LLM-generated Python code. Key features include:

- **Capabilities**: Runs a subset of Python (async/sync, type hints, limited stdlib like `sys`, `os`, `asyncio`), blocks filesystem/network/env access, allows controlled host function calls, supports snapshotting, and enforces resource limits (memory, time, stack depth).
- **Performance**: Near-instant startup (<1μs), comparable runtime speed to CPython (5x faster/slower).
- **Integration**: Callable from Python, Rust, or JavaScript; supports serialization for caching/resuming execution.
- **Limitations**: No classes (soon), third-party libraries, or advanced features like `match` statements.

**Alternatives Comparison**:
- **Docker**: Full Python but slow startup (~195ms), complex setup.
- **Pyodide**: Full Python in WASM but slow (~2800ms) and weak security.
- **Starlark-rust**: Fast but not Python-complete.
- **WASI/Wasmer**: Partial Python, unclear setup.
- **YOLO Python**: Fast but insecure.

**Use Case**: Ideal for AI agents generating code (e.g., Pydantic AI’s CodeMode), avoiding sandbox overhead. Example: LLM writes Python calling tools, Monty executes it safely.
## Links

- [Cloudflare's Code Mode](https://blog.cloudflare.com/code-mode/) : A Cloudflare blog post explaining their Code Mode, which enables AI-driven code execution similar to Monty.
- [Programmatic Tool Calling from Anthropic](https://platform.claude.com/docs/en/agents-and-tools/tool-use/programmatic-tool-calling) : Anthropic's documentation on programmatic tool calling, a key use case for Monty in enabling LLMs to interact with tools securely.
- [Code Execution with MCP from Anthropic](https://www.anthropic.com/engineering/code-execution-with-mcp) : Details about Anthropic's Model Context Protocol (MCP) for code execution, highlighting secure and efficient code execution in AI workflows.
- [Smol Agents from Hugging Face](https://github.com/huggingface/smolagents) : Hugging Face's Smol Agents framework for building AI agents that execute code, aligning with Monty's purpose.
- [Pydantic AI Documentation](https://github.com/pydantic/pydantic-ai) : The Pydantic AI repository, where Monty powers code-mode for secure Python code execution in AI agents.

## Topics

![[topics/Tool/Monty]]

![[topics/Concept/AI Sandboxing]]

![[topics/Concept/Iterative Code Execution]]

![[topics/Concept/Code Serialization]]

![[topics/Concept/Resource Usage Control]]

![[topics/Concept/External Function Integration]]