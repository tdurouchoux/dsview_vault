---
already_read: true
link: https://simonwillison.net/2024/Nov/7/project-verdad/
read_priority: 2
relevance: 0
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2024-11-18'
---

https://simonwillison.net/2024/Nov/7/project-verdad/
## Summary

The VERDAD project, initiated by Rajiv Sinclair and journalist Martina Guzmán, aims to track political misinformation in radio broadcasts across the USA, focusing primarily on Spanish-language content. The project processes around a thousand hours of audio daily from 48 talk radio stations. It employs Gemini 1.5 Flash for transcription and Gemini 1.5 Pro for misinformation detection, generating transcripts, translations, and classifying snippets of possible misinformation for review.

Key components of the project include:

- **Use of LLMs**: The project leverages advanced language models to transcribe audio and identify misinformation, enabled by multi-modal tools developed in recent times.
- **Workflow and Technology**: Prefect orchestrates the workflow, storing audio in Cloudflare R2, followed by transcription and analysis stages using Gemini models and Whisper for accurate timestamping.
- **Prompt Engineering**: The project includes detailed development and iteration of prompts, which are accessible on GitHub, and are crucial for effective misinformation detection.
- **Human Review Mechanism**: A web application facilitates human reviewers to listen to audio snippets, view transcripts and translations, and make corrections, emphasizing the importance of human oversight in AI processes.

VERDAD represents a significant advancement in data journalism, demonstrating the potential of new technologies in addressing misinformation. The team is open to collaboration and continues to evolve the project further.
## Links

- [Prefect - Workflow Orchestration for Data Pipelines](https://github.com/PrefectHQ/prefect) : GitHub repository for Prefect, an open-source workflow orchestration tool used in managing data workflows.
- [VERDAD Project - Prompts for Analyzing Misinformation](https://github.com/PublicDataWorks/verdad/blob/main/prompts/Stage_3_analysis_prompt.md) : A detailed GitHub document outlining the prompts used in the VERDAD project for identifying misinformation in audio transcriptions.
- [VERDAD Project - Available Prompts](https://github.com/PublicDataWorks/verdad/tree/main/prompts) : GitHub repository section where you can find various prompts utilized by the VERDAD project for different stages of analysis.
- [Gist: Climate Change Disinformation Prompts](https://gist.github.com/rajivsinclair/8fb0371f6eda25f9e5cc515cd77abd62) : A Gist containing specific prompts related to climate change disinformation that are utilized in the VERDAD project for analysis.
- [Official Website of VERDAD Project](https://verdad.app/) : The official website for the VERDAD project, detailing its mission and contact information for collaboration.

## Topics

![](topics/Concept/Prompt%20Engineering)

![](topics/Tool/Prefect)

![](topics/Tool/Gemini%201%205%20Flash)

![](topics/Tool/Gemini%201%205%20Pro)

![](topics/Model/Whisper)

![](topics/Platform/Cloudflare%20R2)

![](topics/Dataset/Radio%20Broadcast%20Audio)