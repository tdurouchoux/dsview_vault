---
already_read: true
link: https://docs.astral.sh/uv/guides/projects/
read_priority: 1
relevance: 0
source: Me
tags:
- Development_tool
type: Content
upload_date: '2024-12-14'
---

https://docs.astral.sh/uv/guides/projects/
## Summary

The content outlines the process of managing Python projects using the `uv` tool. Key points include:

- **Project Initialization**: New projects can be created using `uv init`, setting up essential files like `pyproject.toml`, `.python-version`, and a virtual environment.

- **Project Structure**: The structure includes the defined files along with `.venv` for virtual environments and `uv.lock` for locking dependencies to specific versions.

- **Dependency Management**: Dependencies can be added using `uv add`, removed with `uv remove`, and updated with `uv lock --upgrade-package`. Version constraints and other sources, like Git, are supported.

- **Running Commands**: `uv run` ensures commands execute in a consistent environment, syncing the lockfile and environment automatically.

- **Building Distributions**: Distributions can be built with `uv build`, generating files in a `dist/` directory.

The next steps guide users to delve deeper into project management and publishing packages. Overall, `uv` simplifies Python project management with automated dependency handling and environment management.
## Links

- [GitHub repository for uv](https://github.com/astral-sh/uv) : The official GitHub repository for the uv project, containing source code, issues, and documentation.
- [Writing a pyproject.toml](https://packaging.python.org/en/latest/guides/writing-pyproject-toml/) : A guide on how to write and configure a pyproject.toml file for Python projects.
- [Package Index for uv](https://pypi.org/project/uv/) : The official Python Package Index page for the uv package, including installation instructions and version information.

## Topics

![](topics/Library/uv)

![](topics/Concept/pyproject%20toml)

![](topics/Concept/Virtual%20Environment)

![](topics/Concept/Lockfile%20Management)

![](topics/Platform/GitHub%20Actions)

![](topics/Tool/Docker)

![](topics/Platform/GitLab%20CI%20CD)

![](topics/Concept/Dependency%20Management)