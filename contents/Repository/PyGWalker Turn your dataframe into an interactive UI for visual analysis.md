---
already_read: false
link: https://github.com/Kanaries/pygwalker
read_priority: 1
relevance: 0
source: null
tags:
- Data_Visualization
- Data_Analysis
type: Content
upload_date: '2023-03-02'
---

https://github.com/Kanaries/pygwalker
## Summary

PyGWalker is a Python library designed to simplify exploratory data analysis (EDA) and visualization workflows by converting pandas DataFrames into interactive visual interfaces. It integrates Jupyter Notebooks with Graphic Walker, an open-source alternative to Tableau, enabling data scientists to visualize, clean, and annotate data through drag-and-drop operations and natural language queries.

### Key Features:
- **Interactive Data Exploration**: Drag-and-drop interface for creating visualizations, real-time updates, zooming, panning, and filtering.
- **Data Cleaning and Transformation**: Tools for identifying and removing outliers, creating new variables, and transforming data.
- **Advanced Visualization**: Support for various chart types, customization options, and interactive features like tooltips and drill-down capabilities.
- **Integration with Jupyter Notebooks**: Seamless workflow integration.
- **Open-Source and Free**: Customizable and extensible.

### Getting Started:
1. **Installation**:
   ```bash
   pip install pygwalker
   ```
   or
   ```bash
   conda install -c conda-forge pygwalker
   ```

2. **Basic Usage**:
   ```python
   import pandas as pd
   import pygwalker as pyg

   df = pd.read_csv('./bike_sharing_dc.csv')
   walker = pyg.walk(df)
   ```

### Additional Features:
- **Programmatic Export**: Save charts as SVG or PNG files.
- **Streamlit Integration**: Host web versions of PyGWalker without detailed web application knowledge.
- **Privacy Configuration**: Options to control data sharing and updates.

### Development and Contribution:
- Supported environments include Jupyter Notebook, Google Colab, Kaggle, and more.
- Contributions are encouraged in various forms, including code, support, and documentation.

### Resources:
- **Documentation**: Available on the Kanaries website.
- **Community Support**: Discord channel and GitHub issues for support.

PyGWalker aims to streamline the data analysis process, making it more accessible and efficient for data scientists.
## Links

- [PyGWalker Documentation](https://pygwalker-docs.vercel.app/api-reference/jupyter) : Official documentation for PyGWalker, providing detailed information on how to use the library in Jupyter environments.
- [PyGWalker Cloud](https://kanaries.net/pygwalker?from=gh_md) : PyGWalker Cloud service for saving charts, publishing interactive cells as web apps, and using advanced GPT-powered features.
- [PyGWalker on PyPI](https://pypi.org/project/pygwalker) : PyGWalker project page on the Python Package Index, providing installation instructions and package details.
- [PyGWalker on Conda-Forge](https://anaconda.org/conda-forge/pygwalker) : PyGWalker project page on Conda-Forge, providing installation instructions and package details for Conda users.

## Topics

![[topics/Library/DuckDB]]

![[topics/Library/Streamlit]]

![[topics/Library/PyGWalker]]

![[topics/Library/Panel]]

![[topics/Platform/Hex Platform]]

![[topics/Platform/marimo]]

![[topics/Library/runcell]]

![[topics/Library/Graphic Walker]]