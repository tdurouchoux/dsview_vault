---
type: Tool
---

Hamilton is a standardized way to build dataflows (any code that processes data) in Python. It allows users to write each data transformation step as a single Python function, with the function name corresponding to the output variable it computes and the parameter names corresponding to inputs. This tool aims to make it easy to adhere to principles of good system design, such as not breaking often, being easy to triage/debug, easy to understand, and easy to modify. It supports multiple points along the efficient frontier between good code and quick development, making it easier to move along that curve.