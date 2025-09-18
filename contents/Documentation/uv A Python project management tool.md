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

The content provides a guide on managing Python projects using uv, a tool for dependency management and project environment handling. Key points include:

- **Project Initialization**: Creating a new project with `uv init` generates essential files like `pyproject.toml`, `.python-version`, and `main.py`.
- **Project Structure**: Projects consist of files like `pyproject.toml`, `.venv` (virtual environment), `.python-version`, and `uv.lock` (lockfile for dependencies).
- **Dependency Management**: Use `uv add` to add dependencies, `uv remove` to remove them, and `uv lock` to upgrade packages. Dependencies are specified in `pyproject.toml` and resolved in `uv.lock`.
- **Running Commands**: `uv run` executes commands in the project environment, ensuring consistency. Commands can also be run manually after activating the virtual environment.
- **Building Distributions**: `uv build` creates source and binary distributions for the project.
- **Next Steps**: Further details can be found in the projects concept page and command reference.

The guide emphasizes the use of uv for managing project dependencies, environments, and commands, ensuring reproducibility and consistency across different machines.
## Links

- [Pyproject.toml Guide](https://packaging.python.org/en/latest/guides/writing-pyproject-toml/) : Official guide on writing pyproject.toml files for Python projects.
- [uv on PyPI](https://pypi.org/project/uv/) : The uv project page on PyPI, providing package details and installation instructions.

## Topics

![[topics/Tool/uv)]]