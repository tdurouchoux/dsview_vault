---
already_read: true
link: https://library-skills.io/
read_priority: 0
relevance: 4
source: null
tags:
- Development_tool
type: Content
upload_date: '2026-07-26'
---

https://library-skills.io/

## Summary

**Library Skills** is a tool designed to keep AI agents updated with the latest library features and best practices. It ensures agents use current, non-deprecated patterns by embedding official "library skills" in libraries like FastAPI and Streamlit, synchronized with library updates.

Key technical points:
- Installs via `uvx library-skills` (Python) or `npx library-skills` (JavaScript/TypeScript).
- Scans project dependencies, installs/updates skills, and manages symbolic links (relative, Git-committable).
- Supports `.agents/skills` (default) or `.claude/skills` (for Claude Code) directories.
- On Windows, requires Developer Mode or elevated permissions for symlinks; use `--copy` as fallback.
- Non-interactive installs use `--claude` for Claude Code compatibility.
- Addresses LLM limitations (outdated training data) by providing real-time, library-specific guidance.

License: MIT. Documentation: [library-skills.io](https://library-skills.io). Source: [GitHub](https://github.com/tiangolo/library-skills).

## Links

- [Library Skills Official Documentation](https://library-skills.io) : The official documentation for Library Skills, providing detailed information on how to use, install, and configure the tool. It serves as a primary resource for understanding its functionality and integration.
- [Library Skills Source Code](https://github.com/tiangolo/library-skills) : The GitHub repository for Library Skills, containing the source code, issue tracker, and contribution guidelines. This is essential for developers who want to explore, contribute, or understand the implementation.
- [FastAPI Official Documentation](https://fastapi.tiangolo.com) : The official documentation for FastAPI, a modern, fast (high-performance) web framework for building APIs with Python. It is relevant as Library Skills supports FastAPI and includes its own AI skills.
- [Streamlit Official Website](https://streamlit.io) : The official website for Streamlit, an open-source Python library for building interactive web applications for data science and machine learning. It is relevant as Library Skills also supports Streamlit and includes its AI skills.
- [Library Skills on PyPI](https://pypi.org/project/library-skills) : The PyPI page for Library Skills, providing details on how to install the tool using Python's package manager (pip). This is useful for users who want to integrate it into their Python projects.


## Topics

![[topics/Tool/Library Skills]]

![[topics/Concept/AI Agents for Library Usage]]

![[topics/Platform/Agentskills io]]