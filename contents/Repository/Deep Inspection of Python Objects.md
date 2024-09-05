---
already_read: false
link: https://github.com/igrek51/wat
read_priority: 1
source: null
tags:
- Python
type: Content
upload_date: '2024-08-08'
---

https://github.com/igrek51/wat
## Summary

WAT is a Python inspection tool designed for deep inspection of Python objects at runtime. It allows users to investigate an object's type, formatted value, variables, methods, parent types, signatures, documentation, and source code. 

Key features include:
- **Insta-Load**: Quickly debug without installation by executing a provided code snippet in the Python interpreter.
- **Usage**: The tool can be invoked using `wat(object)` or the shorthand `wat / object`. Various modifiers can be applied to customize the output, such as `.short`, `.long`, `.code`, and `.dunder`.
- **Local and Global Inspection**: Users can inspect local and global variables using `wat.locals` and `wat.globals`.
- **Exploration**: WAT can explore modules, functions, and attributes, providing insights into their types and signatures.
- **Debugging**: It integrates with Python's breakpoint for interactive debugging.

WAT is particularly useful for understanding dynamic types in Python, exploring unknown objects, and reviewing code. It has no external dependencies and can be installed via pip.
## Links

1. [WAT Documentation](https://igrek51.github.io/wat/) - Official documentation for the WAT inspection tool, detailing its features and usage.
2. [PyPI - wat-inspector](https://pypi.org/project/wat-inspector) - The package page for installing the WAT inspector via pip, including installation instructions and dependencies.
3. [Rich Inspect](https://github.com/Textualize/rich?tab=readme-ov-file#rich-inspect) - A library that inspired the WAT inspector, providing advanced features for inspecting Python objects.
## Topics

- [[topics/Library/wat-inspector]]
- [[topics/Concept/Object Inspection]]
- [[topics/Concept/Dynamic Typing]]
- [[topics/Concept/Debugging Techniques]]
- [[topics/Concept/Python Interpreter]]