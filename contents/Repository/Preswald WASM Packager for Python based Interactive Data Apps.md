---
already_read: false
link: https://github.com/StructuredLabs/preswald
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Data_Visualization
- Python
type: Content
upload_date: '2025-02-18'
---

https://github.com/StructuredLabs/preswald
## Summary

Preswald is a WASM packager for Python-based interactive data apps, enabling the bundling of complex data workflows, particularly visualizations, into single files. These files are runnable completely in-browser using Pyodide, DuckDB, Pandas, and various plotting libraries like Plotly and Matplotlib. Key features include:

- **Code-based**: Write apps in Python.
- **File-first**: One command creates a fully-packaged .html app.
- **Built for computation**: Use Pyodide + DuckDB directly in-browser.
- **Composable UI**: Prebuilt components like tables, charts, forms.
- **Reactive engine**: Only re-run what's needed, powered by a DAG of dependencies.
- **Local execution**: No server required, runs offline.
- **AI-ready**: Apps are fully inspectable and modifiable by agents.

**Installation**:
```bash
pip install preswald
```

**Quick Start**:
```bash
preswald init my_app
cd my_app
preswald run
```

**Use Cases**:
- Analyst dashboards
- Interactive reports
- Data inspection tools
- Offline kits
- Experiment panels

Preswald is licensed under the Apache 2.0 License and has a community-driven development model with contributions from various developers.
## Links

- [Preswald Documentation](https://docs.preswald.com) : Official documentation for Preswald, providing detailed guides and references for using the tool.
- [Preswald Official Website](https://www.preswald.com/) : The official website for Preswald, offering additional resources and information about the project.
- [Preswald PyPI](https://pypi.org/project/preswald/) : PyPI page for Preswald, where you can find installation instructions and package details.

## Topics

![](topics/Platform/Preswald)

![](topics/Concept/Pyodide)

![](topics/Library/DuckDB)

![](topics/Library/Plotly)

![](topics/Library/Matplotlib)