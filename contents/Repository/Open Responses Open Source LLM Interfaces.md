---
already_read: true
link: https://github.com/openresponses/openresponses
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2026-02-01'
---

https://github.com/openresponses/openresponses
## Summary

Open Responses is an open-source specification for interoperable LLM interfaces, inspired by the OpenAI API. It defines a shared request/response model, streaming semantics, and tool invocation patterns for consistent client-provider communication. Key aspects include:

- Agentic loop for model-tool interaction
- Items as atomic context units with state machines
- Semantic streaming events for predictable client behavior
- Extensibility for provider-specific tools without breaking core schema

The repository contains:
- Full specification (public/openapi/openapi.json)
- Website documentation (src/pages)
- Compliance tests (bin/compliance-test.ts)

Compliance testing is available via web UI (https://www.openresponses.org/compliance) and CLI, with options to filter specific tests. The project is primarily written in TypeScript (45.2%), Python (28.9%), and MDX (13.7%).
## Links

- [Open Responses Compliance Tester](https://www.openresponses.org/compliance) : Interactive compliance tester for Open Responses, allowing users to verify adherence to the Open Responses specification.
- [Open Responses Website](https://openresponses.org) : Official website for Open Responses, providing detailed documentation and resources about the open-source specification for multi-provider, interoperable LLM interfaces.

## Topics

![[topics/Concept/Open Responses]]