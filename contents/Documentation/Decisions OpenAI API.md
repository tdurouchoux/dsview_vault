---
already_read: true
link: https://developers.openai.com/api/docs/guides/decisions
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2026-10-17'
---

https://developers.openai.com/api/docs/guides/decisions

## Summary

The Decisions API is a new OpenAI endpoint that evaluates text or images and returns typed answers (probabilities, choices, or scores) ~10x faster than the Responses API, enabling classification, routing, and prioritization in applications.

**Core capability**
- Dedicated POST /v1/decisions endpoint with only gpt-6-luna model currently supported.
- Input: shared evidence (text string or user messages with text + images).
- Questions array: each question has type (predicate, choice, score), name, instructions, and type-specific options.

**Question types**
- predicate: returns probability (0–1) that a condition is true.
- choice: selects one value from supplied options; returns choice, probabilities per option, and confidence.
- score: rates input against ordered levels; returns probability-weighted average score, confidence, and per-level probabilities.

**Performance & cost**
- ~10× faster than Responses API.
- Input pricing: $0.10 per 1M tokens (no output or cache token charges).
- Regional processing premiums and long-context multipliers apply.

**Compliance & data**
- Supports Zero Data Retention (ZDR) and HIPAA for eligible customers.
- Data residency available in US and Europe (EEA + Switzerland).

**Integration**
- Images must be inline base64 data URLs.
- SDK examples require: Python 3.26.0+, JS 7.30.0+, Go 3.73.0+, Ruby 0.101.0+, Java 4.78.0+.
- Public beta, GA expected in coming weeks.

## Links

- [OpenAI Decisions API Documentation](https://platform.openai.com/decisions) : Official documentation for the OpenAI Decisions API, including guides, API reference, and examples for making structured decisions using text and images.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) : A GitHub repository containing practical examples, notebooks, and code snippets for building applications with OpenAI models, including the Decisions API.
- [OpenAI Academy](https://openai.com/academy/) : Educational resources, online trainings, and learning materials provided by OpenAI to help developers understand and utilize their models effectively.
- [OpenAI Developer Blog](https://developers.openai.com/blog) : A blog featuring articles, tutorials, and updates from OpenAI developers, including insights into new features, best practices, and use cases for APIs like Decisions.


## Topics

![[topics/Model/gpt 6 luna]]

![[topics/Tool/Decisions API]]

![[topics/Concept/Structured Outputs]]

![[topics/Platform/OpenAI API]]