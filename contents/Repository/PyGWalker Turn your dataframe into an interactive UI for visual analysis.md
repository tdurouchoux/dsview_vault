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

PyGWalker is a Python library designed to simplify exploratory data analysis (EDA) and visualization workflows by transforming pandas DataFrames into interactive visual interfaces. It integrates Jupyter Notebooks with Graphic Walker, an open-source alternative to Tableau, enabling data scientists to visualize, clean, and annotate data through drag-and-drop operations and natural language queries.

### Key Features:
- **Interactive Data Exploration**: Drag-and-drop interface for easy visualization creation, real-time updates, and capabilities to zoom, pan, and filter data.
- **Data Cleaning and Transformation**: Visual tools for identifying and removing outliers, creating new variables, and transforming data.
- **Advanced Visualization**: Support for various chart types, customization options, and interactive features like tooltips and drill-down capabilities.
- **Integration with Jupyter Notebooks**: Seamless workflow integration.
- **Open-Source and Free**: Allows for customization and extension.

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

### Advanced Features:
- **Programmatic Export**: Save charts to files or export as images.
- **Streamlit Integration**: Host web versions of PyGWalker without detailed web application knowledge.
- **Privacy Configuration**: Options to control data sharing and updates.

### Development and Contribution:
- Supported environments include Jupyter Notebook, Google Colab, Kaggle, and more.
- Contributions are encouraged, including answering questions, reporting bugs, and contributing code.

### Resources:
- **PyGWalker Cloud**: Save charts to the cloud, publish interactive cells as web apps, and use advanced GPT-powered features.
- **Documentation and Support**: Available on the Kanaries website and GitHub.

PyGWalker aims to streamline the data analysis process, making it more accessible and efficient for data scientists.
## Links

- [PyGWalker Documentation](https://docs.kanaries.net/pygwalker/use-pygwalker-with-streamlit) : Documentation on how to use PyGWalker with Streamlit, providing detailed instructions and examples.
- [PyGWalker API Reference](https://pygwalker-docs.vercel.app/api-reference/jupyter) : API reference for PyGWalker, detailing the available functions and parameters for Jupyter Notebook integration.
- [PyGWalker GitHub Repository](https://github.com/Kanaries/pygwalker) : The official GitHub repository for PyGWalker, containing the source code, issues, and pull requests.

## Topics

![](topics/Library/PyGWalker)

![](topics/Concept/Graphic%20Walker)

![](topics/Library/runcell)

![](topics/Library/Streamlit)

![](topics/Library/Panel)

![](topics/Library/DuckDB)