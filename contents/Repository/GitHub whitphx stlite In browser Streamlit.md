---
already_read: true
link: https://github.com/whitphx/stlite
read_priority: 1
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2025-01-02'
---

https://github.com/whitphx/stlite
## Summary

Stlite is a project that enables Streamlit, a Python web app framework for data apps, to run entirely in a web browser using Pyodide and WebAssembly. Key points include:

- **Browser-based Execution**: Streamlit apps run in the browser without needing a server, leveraging Pyodide and WebAssembly.
- **Integration Methods**: Stlite can be integrated into web pages using `<streamlit-app>` tags or the `mount()` JavaScript function.
- **File Handling**: Supports loading files from strings, URLs, or archive files, and mounting them to a virtual file system.
- **Multipage Apps**: Supports multipage Streamlit apps by specifying multiple files.
- **Configuration**: Allows customization of Streamlit configuration via the `streamlitConfig` option.
- **Package Management**: Enables installation of Python packages with specific options.
- **File Persistence**: Supports persistent file storage using IndexedDB.
- **HTTP Requests**: Provides support for HTTP requests using libraries like `requests`, `urllib`, and `urllib3`.
- **SharedWorker Mode**: Reduces resource consumption by running multiple apps in a single worker.
- **Limitations**: Includes known issues such as non-functional `st.spinner()`, `st.bokeh_chart()`, and differences in handling certain data types.
- **Top-level Await**: Supports top-level await for async operations, useful for non-blocking operations like `asyncio.sleep()` and `pyodide.http.pyfetch()`.

Stlite is open-source under the Apache-2.0 license and has a community of contributors. It is sponsored by Streamlit (Snowflake), Hal9, and RAKUDEJI Inc.
## Links

- [Streamlit meets WebAssembly - stlite](https://onlyweb.hashnode.dev/is-this-the-easiest-way-to-build-your-streamlit-app) : A blog post covering technical surveys and usages of the online editor Stlite Sharing, self-hosting apps, and the desktop app bundler.
- [Streamlit Community](https://discuss.streamlit.io/t/new-library-stlite-a-port-of-streamlit-to-wasm-powered-by-pyodide/25556) : The Stlite thread at the Streamlit online forum.
- [Streamlit](https://streamlit.io/) : Streamlit is a Python web app framework for the fast development of data apps.

## Topics

![](topics/Library/Stlite)

![](topics/Concept/Pyodide)

![](topics/Concept/WebAssembly)