---
already_read: true
link: https://github.com/whitphx/stlite
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2025-01-02'
---

https://github.com/whitphx/stlite
## Summary

Stlite is a project that allows Streamlit applications to run entirely in a web browser using Pyodide and WebAssembly. It facilitates the creation of interactive data applications without needing a server. Key features include:

- **Web Integration**: Developers can mount Streamlit apps directly into HTML pages through script imports.
- **Dependency Management**: The ability to install Python packages on demand for app functionality.
- **File System**: Stlite utilizes a virtual file system, which is ephemeral by default but can be made persistent with IndexedDB.
- **Async Support**: The use of top-level await is encouraged in Stlite, replacing traditional asyncio.run() due to its browser-based environment.
- **Limitations**: Some Streamlit functions and libraries may not work as expected, such as blocking methods causing UI issues and certain package compatibility problems.

Examples provided illustrate how to set up apps with various configurations, handle HTTP requests, and maintain state across sessions. Resources for further learning and sample applications are also available.
## Links

- [Streamlit Documentation on Multipage Apps](https://docs.streamlit.io/library/get-started/multipage-apps) : Official guide by Streamlit explaining how to create multipage applications.
- [Using Fetch API in Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) : MDN documentation on how to use the Fetch API for making network requests.
- [Pyodide HTTP API Documentation](https://pyodide.org/en/stable/usage/api/python-api/http.html#pyodide.http.open_url) : Documentation for HTTP functionalities available in Pyodide.
- [Filesystem API Documentation](https://emscripten.org/docs/api_reference/Filesystem-API.html) : Comprehensive guide on the Filesystem API used with Emscripten, relevant for managing files in Pyodide.
- [Pyodide's unpackArchive Function](https://pyodide.org/en/stable/usage/api/js-api.html#pyodide.unpackArchive) : Documentation for the function that allows loading archive files in Pyodide.

## Topics

![](topics/Platform/Stlite)

![](topics/Library/Streamlit)

![](topics/Concept/WebAssembly)

![](topics/Library/Pyodide)

![](topics/Concept/Serverless%20Computing)

![](topics/Concept/Client%20side%20Processing)