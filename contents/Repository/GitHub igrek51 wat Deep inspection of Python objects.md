---
already_read: false
link: https://github.com/igrek51/wat
read_priority: 1
relevance: 0
source: null
tags:
- Python
type: Content
upload_date: '2024-08-08'
---

https://github.com/igrek51/wat
## Summary

WAT is a Python inspection tool designed for deep exploration of Python objects at runtime. It allows users to interactively investigate an object's type, formatted value, variables, methods, parent types, signature, documentation, and source code, particularly useful for debugging and understanding complex data structures.

Key features include:
- **Interactive Inspection**: Use `wat(object)` or shortcuts like `wat / object` for quick inspections.
- **Modifiers**: Apply modifiers to control the output (e.g., `.short`, `.long`, `.code`).
- **Namespace Inspection**: Functions to inspect local and global variables (`wat.locals`, `wat.globals`).
- **Type and Method Lookup**: Easily identify object types and methods with their signatures.
- **Nested Structure Formatting**: Provides prettified outputs for complex collections.
- **Debugging Support**: Integrates with Python's breakpoint for interactive debugging.
- **Color Customization**: Allows customization of output color themes via environment variables.

WAT does not require external dependencies and can be quickly loaded in an ongoing session with minimal setup, making it a convenient tool for Python developers.
## Links

- [Deep Inspection of Python Objects](https://igrek51.github.io/wat) : The official documentation for WAT, a tool for inspecting Python objects, showing usage examples and modifiers.
- [WAT on PyPI](https://pypi.org/project/wat) : The PyPI page for the WAT package, allowing users to install the library using pip.
- [Rich Inspect on GitHub](https://github.com/Textualize/rich?tab=readme-ov-file#rich-inspect) : Documentation for Rich, a library for rich text and beautiful formatting in Python, including its inspect functionality.
- [WAT Short Syntax Example](https://github.com/igrek51/wat/blob/master/docs/img/wat-short-types.png?raw=true) : An example image illustrating the short syntax feature of WAT for inspecting Python objects.
- [WAT Locals Inspection Example](https://github.com/igrek51/wat/blob/master/docs/img/wat-locals.png?raw=true) : An example image demonstrating how to inspect local variables using the WAT tool.

## Topics

![](topics/Library/wat)

![](topics/Concept/Dynamic%20Typing%20in%20Python)

![](topics/Concept/Object%20Inspection)

![](topics/Concept/Interactive%20Debugging)

![](topics/Tool/Python%20Interpreter)