---
type: Library
---

Guardrails is a library designed to specify structure and type, as well as validating and correcting the outputs of large language models. It works by defining a .rail specification that allows for defining the structure of the requested output, validators to ensure the values meet a given quality criteria, and corrective actions such as re-asking the LLM or filtering out the invalid output if the validations are not met.