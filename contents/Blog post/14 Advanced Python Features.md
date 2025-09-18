---
already_read: true
link: https://blog.edward-li.com/tech/advanced-python-features/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Python
type: Content
upload_date: '2025-04-29'
---

https://blog.edward-li.com/tech/advanced-python-features/
## Summary

Python is widely used but often underappreciated due to its simplicity. The article discusses 14 advanced Python features that are underrated or unique, compiled by Edward Li. These features were originally shared in a 14-day series on X/Twitter.

1. **Typing Overloads**: The `@overload` decorator allows defining multiple signatures for the same function, helping with type checking but not creating multiple function versions.

2. **Keyword-only and Positional-only Arguments**: These arguments control how parameters can be passed, useful for API developers to enforce argument usage.

3. **Future Annotations**: Discusses the history of Python's typing system and the use of `from __future__ import annotations` to handle forward references and reduce runtime overhead.

4. **Generics**: Introduces Python's generics, with a new syntax in Python 3.12, and discusses type aliases and variadic generics.

5. **Protocols**: Protocols allow for structural subtyping, enabling type checking based on the structure or behavior of classes without using interfaces or inheritance.

6. **Context Managers**: Context managers simplify the process of setting up and tearing down resources, with the `contextlib` module providing a decorator to handle boilerplate code.

7. **Structural Pattern Matching**: Introduced in Python 3.10, this feature provides a powerful alternative to traditional conditional logic, with destructuring and guard clauses.

8. **Python Slots**: Slots optimize attribute access by using an array-like structure, potentially speeding up class creation and access.

9. **Python Nitpicks**: Quick syntax tips to clean up Python code, including for-else statements, the walrus operator, short-circuit evaluation, and operator chaining.

10. **Advanced f-string String Formatting**: F-strings allow for more control over string formatting, including debug expressions, number formatting, string padding, date formatting, and percentage formatting.

11. **Cache / lru_cache**: The `@cache` decorator speeds up recursive functions and expensive calculations, with `@lru_cache` providing explicit control of cache size.

12. **Python Futures**: The `concurrent.futures` module provides Promise-like concurrency control, with Futures allowing for async operations and control over exceptions, timeouts, and task stopping.

13. **Proxy Properties**: Demonstrates how to make class attributes act as both methods and properties using descriptors and dunder methods.

14. **Metaclasses**: Metaclasses are powerful but complex features that allow customization and modification of class creation. They are rarely needed but can be useful for specific use cases.

The article concludes with a reminder that metaclasses are advanced and often unnecessary, but powerful for unique problems. Real-world examples include Python's ABC and Enum implementations, and usage in libraries like Django and SQLAlchemy.
## Links

- [Python Type Hints: How to use @overload](https://adamj.eu/tech/2021/05/29/python-type-hints-how-to-use-overload/) : This link provides a detailed guide on how to use the @overload decorator in Python for type hints, which is a feature discussed in the content.
- [Python’s F-String for String Interpolation and Formatting](https://realpython.com/python-f-strings/) : This link offers a comprehensive guide on using f-strings in Python, including advanced formatting techniques mentioned in the content.
- [Python’s Format Mini-Language for Tidy Strings](https://realpython.com/python-format-mini-language/) : This link explains the Format Mini-Language used within f-strings, providing examples and best practices for string formatting in Python.
- [Python Descriptors: An Introduction](https://realpython.com/python-descriptors/) : This link introduces Python descriptors, which are used in the content to explain how proxy properties work under the hood.
- [Python Metaclasses](https://realpython.com/python-metaclasses/) : This link provides an in-depth explanation of metaclasses in Python, covering their usage and examples, which is a topic discussed in the content.

## Topics

![[topics/Concept/Context Managers]]

![[topics/Concept/Typing Overloads]]

![[topics/Concept/Future Annotations]]

![[topics/Concept/Advanced f string String Formatting]]

![[topics/Concept/Keyword only and Positional only Arguments]]

![[topics/Concept/Python Slots]]

![[topics/Concept/Python Nitpicks]]

![[topics/Concept/Protocols]]

![[topics/Concept/Generics]]

![[topics/Concept/Cache lru_cache]]

![[topics/Concept/Structural Pattern Matching]]