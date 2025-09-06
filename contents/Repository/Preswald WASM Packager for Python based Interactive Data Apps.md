---
already_read: false
link: https://github.com/StructuredLabs/preswald
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Data_Visualization
- Development_tool
type: Content
upload_date: '2025-02-18'
---

https://github.com/StructuredLabs/preswald
## Summary

Preswald is a WASM packager for Python-based interactive data apps, enabling the bundling of complex data workflows, particularly visualizations, into single files. These files are runnable completely in-browser using Pyodide, DuckDB, Pandas, and various plotting libraries like Plotly and Matplotlib. Key features include:

- **Code-based**: Write apps in Python.
- **File-first**: One command creates a fully-packaged .html app.
- **Built for computation**: Use Pyodide + DuckDB directly in-browser.
- **Composable UI**: Prebuilt components like tables, charts, and forms.
- **Reactive engine**: Only re-run what's needed, powered by a DAG of dependencies.
- **Local execution**: No server required, runs offline.
- **AI-ready**: Apps are fully inspectable and modifiable by agents.

**Installation**: Available via pip (`pip install preswald` or `uv pip install preswald`).

**Quick Start**:
1. Initialize a new app with `preswald init my_app`.
2. Edit `hello.py` to build your app.
3. Run locally with `preswald run`.

**Configuration**: Uses a `preswald.toml` file for metadata, runtime settings, UI branding, and data sources.

**Use Cases**:
- Analyst dashboards.
- Interactive reports.
- Data inspection tools.
- Offline kits.
- Experiment panels.

**Documentation and Community**: Full documentation, contributing guidelines, and community forums are available. Preswald is licensed under the Apache 2.0 License.
## Links

- [Preswald Documentation](https://docs.preswald.com) : The official documentation for Preswald, providing detailed guides and information on how to use the tool effectively.
- [Preswald Installation](https://pypi.org/project/preswald/) : The PyPI page for installing Preswald, including installation instructions and package details.

## Topics

![](topics/Tool/Preswald)

![](topics/Concept/Pyodide)

![](topics/Library/DuckDB)