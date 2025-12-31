---
type: Concept
---

Token-Oriented Object Notation (TOON) is a compact, human-readable encoding of the JSON data model designed to minimize tokens and enhance structure for Large Language Model (LLM) inputs. It combines YAML's indentation-based structure for nested objects with a CSV-style tabular layout for uniform arrays, making it particularly efficient for uniform arrays of objects. TOON aims to be a lossless, drop-in representation of JSON, optimizing token usage while maintaining readability and reliability for LLMs. It is intended to be used as a translation layer, where JSON is used programmatically and encoded as TOON for LLM input.