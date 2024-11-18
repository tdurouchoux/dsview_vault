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

WAT is a Python inspection tool designed for deep exploration of Python objects at runtime. It allows users to investigate an object's type, formatted value, variables, methods, parent types, signatures, documentation, and source code, making it particularly useful for debugging and understanding complex data structures.

Key features include:
- **Insta-Load**: Quickly use the inspector without installation by executing a provided code snippet in the Python interpreter.
- **Usage**: The tool can be invoked using `wat(object)` or the shorthand `wat / object`. Various modifiers can be applied to customize the output, such as `.short`, `.long`, `.code`, and more.
- **Local and Global Inspection**: Users can inspect local and global variables using `wat.locals` and `wat.globals`.
- **Exploration of Modules and Functions**: The tool can list methods, attributes, and even the source code of functions, aiding in understanding how to use unknown objects.
- **Prettified Output**: Nested structures are displayed in a readable format, enhancing clarity during debugging.

WAT is inspired by the Rich Inspect library and is available under the MIT license. It has no external dependencies, making it easy to integrate into existing Python projects.
## Links

1. [WAT Documentation](https://igrek51.github.io/wat) - Official documentation for the WAT inspection tool, detailing its features and usage.
2. [wat-inspector on PyPI](https://pypi.org/project/wat-inspector) - The package page for WAT on the Python Package Index, where you can install it via pip.
3. [Rich Inspect](https://github.com/Textualize/rich?tab=readme-ov-file#rich-inspect) - A GitHub repository for the Rich library, which includes an inspection feature that inspired WAT.
4. [WAT Inspection Code](https://github.com/igrek51/wat/blob/master/wat/inspection/inspection.py) - The source code for the inspection functionality of the WAT tool, useful for understanding its implementation.
5. [WAT Example: Nested Dict Pretty](https://github.com/igrek51/wat/blob/master/docs/img/wat-nested-dict-pretty.png?raw=true) - An example image demonstrating how WAT prettifies nested dictionaries for better readability.
## Topics

![](topics/Library/wat%20inspector)

![](topics/Concept/Object%20Inspection)

![](topics/Product/Insta%20Load)

![](topics/Concept/Dynamic%20Typing)

![](topics/Concept/Modifiers)