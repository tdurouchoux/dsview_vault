---
already_read: false
link: https://perspective.finos.org/docs/python/
read_priority: 1
source: null
tags:
- Python
type: Content
upload_date: '2023-09-28'
---

https://perspective.finos.org/docs/python/
## Summary

Perspective for Python utilizes the same C++ data engine as its WebAssembly counterpart, offering a similar API to JavaScript with added support for Python data structures like NumPy and Pandas. Key features include:

- **Session Management**: PerspectiveManager allows integration with server systems (e.g., Tornado, AIOHTTP) for managing virtual tables accessible by multiple clients.
- **Data Handling**: Supports various data formats, including pandas.DataFrame and NumPy arrays, with specific methods for creating tables and views.
- **JupyterLab Integration**: PerspectiveWidget enables interactive data visualization within JupyterLab, compatible with JupyterLab 3 and Jupyter Notebook 6.
- **Callbacks**: Provides on_update and on_delete callbacks for real-time data updates.
- **Async and Multi-threading Support**: Allows asynchronous operations and multi-threading for improved performance.
- **Client/Server Architecture**: Facilitates distributed data handling, enabling multiple clients to interact with a common server-side table.
- **WebSocket Communication**: Uses PerspectiveTornadoHandler for seamless integration between Python and JavaScript, allowing real-time data updates and interactions.

Installation can be done via PyPI or Anaconda, and the guide covers various examples and configurations for effective usage.
## Links

1. [NumPy](https://numpy.org/) - A fundamental package for scientific computing with Python, providing support for arrays and matrices.
2. [Pandas](https://pandas.pydata.org/) - A powerful data manipulation and analysis library for Python, ideal for working with structured data.
3. [Apache Arrow](https://arrow.apache.org/) - A cross-language development platform for in-memory data, designed to accelerate analytics and data processing.
4. [Tornado websockets](https://www.tornadoweb.org/en/stable/websocket.html) - Documentation for Tornado's WebSocket support, which is essential for real-time web applications.
5. [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - An interactive development environment for Jupyter notebooks, which supports the PerspectiveWidget for data visualization.
## Topics

- [[topics/Library/perspective-python]]
- [[topics/Library/PerspectiveWidget]]
- [[topics/Library/PerspectiveManager]]
- [[topics/Library/PerspectiveTornadoHandler]]
- [[topics/Library/PerspectiveAIOHTTPHandler]]