---
already_read: true
link: https://github.com/cyclotruc/gitingest
read_priority: 5
relevance: 0
source: Alpha Signal
tags:
- Development_tool
type: Content
upload_date: '2024-12-28'
---

https://github.com/cyclotruc/gitingest
## Summary

Gitingest is a tool designed to transform Git repositories into text extracts suitable for Large Language Models (LLMs). It offers both a command-line interface (CLI) and a Python package for easy integration. Key features include:

1. **Easy Code Context**: Generates a text digest from a Git repository URL or a directory.
2. **Smart Formatting**: Optimizes output for LLM prompts.
3. **Statistics**: Provides insights into file and directory structure, extract size, and token count.
4. **CLI Tool**: Allows analysis and text dump creation from the command line.
5. **Python Package**: Enables programmatic use within Python code.
6. **Browser Extension**: Available for Chrome and Firefox to quickly access digests.
7. **Self-Hosting**: Can be deployed using Docker for local or cloud-based use.

**Requirements**:
- Python 3.8+
- GitHub Personal Access Token (PAT) for private repositories.

**Installation**:
- Install via pip: `pip install gitingest` or `pip install gitingest[server]` for server dependencies.
- For better management, use pipx: `pipx install gitingest`.

**Usage**:
- **CLI**: `gitingest /path/to/directory` or `gitingest https://github.com/username/repo`.
- **Python Package**: `from gitingest import ingest; summary, tree, content = ingest("path/to/directory")`.
- **Browser Extension**: Replace 'hub' with 'ingest' in any GitHub URL to access the digest.
- **Self-Hosting**: Use Docker to run the application locally or on a server.

**Contributing**:
- Non-technical contributions include creating issues, spreading the word, and using the tool.
- Technical contributions involve improving the codebase, with detailed instructions in CONTRIBUTING.md.

**Stack**:
- Frontend: Tailwind CSS
- Backend: FastAPI
- Templating: Jinja2
- Token Estimation: tiktoken
- Analytics: Posthog
- Error Tracking: Sentry

**Project Growth**:
- Active community with 12.1k stars and 892 forks.
- Regular updates and releases.
## Links

- [Gitingest PyPI](https://pypi.org/project/gitingest) : Gitingest project page on PyPI, the Python Package Index.
- [Gitingest Chrome Extension](https://chromewebstore.google.com/detail/adfjahbijlkjfoicpjkhjicpjpjfaood) : Gitingest Chrome extension page in the Chrome Web Store.
- [Gitingest Firefox Add-on](https://addons.mozilla.org/firefox/addon/gitingest) : Gitingest Firefox add-on page in the Firefox Add-ons store.
- [Gitingest GitHub Repository](https://github.com/coderamp-labs/gitingest) : The main GitHub repository for the Gitingest project.

## Topics

![](topics/Tool/Gitingest)