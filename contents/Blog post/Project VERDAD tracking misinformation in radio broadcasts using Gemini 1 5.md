---
already_read: true
link: https://simonwillison.net/2024/Nov/7/project-verdad/
read_priority: 2
relevance: 0
source: Data Elixir
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2024-11-18'
---

https://simonwillison.net/2024/Nov/7/project-verdad/
## Summary

The VERDAD project, developed by Public Data Works and journalist Martina Guzmán, aims to track misinformation in Spanish-language radio broadcasts across the USA. The project uses a combination of audio recording, transcription, and analysis with large language models (LLMs) to identify and categorize potential misinformation. The technology stack includes Prefect for workflow orchestration, Gemini 1.5 for transcription and misinformation detection, and Whisper for generating timestamps. The project processes around a thousand hours of audio daily, making it feasible to analyze vast amounts of content that would be impossible for humans to review manually. The human review process involves a web application that provides context and allows reviewers to listen to audio snippets, update categories, and add comments. The project is under active development, and the team is open to collaboration. The use of new multi-modal LLM tools like Gemini 1.5 Flash has made such projects more affordable and feasible compared to just a year ago.
## Links

- [VERDAD GitHub Repository](https://github.com/PublicDataWorks/verdad/tree/main/prompts) : GitHub repository containing the prompts used by VERDAD for misinformation detection in radio broadcasts.
- [VERDAD Project Website](https://verdad.app/) : Official website of the VERDAD project, providing more information and contact details for collaboration.

## Topics

![](topics/Concept/Data%20Journalism)

![](topics/Model/Gemini)

![](topics/Model/Whisper)

![](topics/Concept/Prompt%20Engineering)

![](topics/Concept/Workflow%20Orchestration)

![](topics/Concept/Prefect)