---
already_read: true
link: https://pixi.prefix.dev/latest/
read_priority: 0
relevance: 4
source: null
tags:
- Development_tool
type: Content
upload_date: '2026-04-25'
---

https://pixi.prefix.dev/latest/
## Summary

Pixi is a modern, fast, and reproducible package management tool supporting Python, C/C++, Java, Rust, Node.js, and CLI tools. Key features include:

- **Reproducibility**: Isolated environments with lockfiles, disk-efficient storage via hard links.
- **Multi-language & platform support**: Works on Linux, macOS, Windows, etc.
- **Task management**: Built-in task runner for complex pipelines.
- **Multiple environments**: Compose environments in one manifest.
- **Global tools**: Safely install and manage global tools (e.g., `gh`, `nvim`).

**Comparison to other tools**:
- Supports Python, multiple languages, lockfiles, task running, and workspace management (unlike `conda`, `pip`, `poetry`, or `uv`).
- Defaults to `conda-forge` (30k+ packages) with optional custom channels.

**Installation**:
```bash
curl -fsSL https://pixi.sh/install.sh | sh  # Linux/macOS
irm -useb https://pixi.sh/install.ps1 | iex  # Windows
```

**Quick Start**:
```bash
pixi init hello-world
cd hello-world
pixi add python
pixi run python -c 'print("Hello World!")'
```

**Global tools**:
```bash
pixi global install gh nvim ipython
```

**Developers praise** Pixi for seamless PyPI/conda-forge integration and global tool management.

**Links**: [GitHub](https://github.com/prefix-dev/pixi), [Discord](https://discord.gg/kKV8Zxyzz8), [Prefix.dev](https://prefix.dev), [conda-forge](https://conda-forge.org).
## Links

- [Pixi GitHub Repository](https://github.com/prefix-dev/pixi) : Official GitHub repository for Pixi, containing the source code, issue tracker, and contribution guidelines.
- [Pixi Installation Script (Linux & macOS)](https://pixi.sh/install.sh) : Installation script for Pixi on Linux and macOS, providing a quick way to set up Pixi.
- [Pixi Installation Script (Windows)](https://pixi.sh/install.ps1) : Installation script for Pixi on Windows, enabling easy setup in PowerShell environments.
- [conda-forge Package Repository](https://conda-forge.org/) : The conda-forge community-driven repository, which Pixi uses as its default package source containing over 30,000 packages.
- [Rattler (Backend of Pixi)](https://github.com/conda/rattler) : The Rust-based backend for Pixi, providing core functionality for package management and environment handling.

## Topics

![[topics/Tool/Pixi]]

![[topics/Concept/Lockfile]]

![[topics/Concept/Task Runner]]

![[topics/Concept/Workspace Management]]

![[topics/Concept/Global Tools]]

![[topics/Platform/conda forge]]

![[topics/Concept/Portability Software]]

![[topics/Tool/uv]]