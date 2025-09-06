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

The content provides a guide on managing Python projects using a tool called uv. Here are the key points:

- **Project Initialization**: Create a new project with `uv init` which sets up essential files like `pyproject.toml`, `.python-version`, and a simple `main.py`.
- **Project Structure**: A project includes files like `.venv` (virtual environment), `pyproject.toml` (project metadata), `.python-version` (Python version), and `uv.lock` (dependency lockfile).
- **Dependencies Management**: Use `uv add` to add dependencies, `uv remove` to remove them, and `uv lock --upgrade-package` to upgrade specific packages. Dependencies are specified in `pyproject.toml` and resolved in `uv.lock`.
- **Version Management**: Check the project version using `uv version` with options for short output or JSON format.
- **Running Commands**: Use `uv run` to execute scripts or commands within the project environment, ensuring consistency. Alternatively, manually sync and activate the environment.
- **Building Distributions**: Build project distributions (source and wheel) using `uv build`, which places artifacts in a `dist/` directory.
- **Next Steps**: Further learning can be done through the projects concept page, command reference, or guides on publishing packages.

The guide emphasizes the use of uv for managing Python projects, focusing on dependency management, environment consistency, and project distribution.
## Links

- [Pyproject.toml guide](https://packaging.python.org/en/latest/guides/writing-pyproject-toml/) : Official guide on writing pyproject.toml files for Python projects.

## Topics

![](topics/Tool/uv)