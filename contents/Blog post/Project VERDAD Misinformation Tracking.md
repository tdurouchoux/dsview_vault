---
already_read: true
link: https://simonwillison.net/2024/Nov/7/project-verdad/?utm_campaign=Data_Elixir&utm_source=Data_Elixir_510
read_priority: 2
source: Data Elixir
tags:
- Data_Engineering
- Natural_Language_Processing
- Generative_AI
- AI_regulation
type: Content
upload_date: '2024-11-18'
---

https://simonwillison.net/2024/Nov/7/project-verdad/?utm_campaign=Data_Elixir&utm_source=Data_Elixir_510
## Summary

The VERDAD project, led by Rajiv Sinclair and journalist Martina Guzmán, aims to track misinformation in radio broadcasts across the USA, focusing primarily on Spanish-language stations. It utilizes advanced LLM tools, specifically Gemini 1.5, to process approximately 1,000 hours of audio daily, which is beyond manual capabilities.

The project involves several key steps: recording audio from radio stations, transcribing it using Gemini 1.5 Flash, and analyzing the transcripts with Gemini 1.5 Pro to identify misinformation snippets. These snippets are then timestamped using the Whisper model, translated into English, and categorized for human review.

The prompts used for misinformation detection are available on GitHub and have been iteratively developed to enhance accuracy. The final output is presented in a web application that allows human reviewers to listen to audio snippets, view transcripts, and provide feedback.

VERDAD exemplifies the potential of modern LLM tools in data journalism, making previously unfeasible projects possible. The team is open to collaboration and further development in this space.
## Links

1. [VERDAD GitHub Repository](https://github.com/PublicDataWorks/verdad/) - The main repository for the VERDAD project, containing code and documentation.
2. [VERDAD Prompts](https://github.com/PublicDataWorks/verdad/tree/main/prompts) - A collection of prompts used in the VERDAD project for misinformation detection.
3. [Prefect](https://github.com/PrefectHQ/prefect) - The workflow orchestration system used in the VERDAD project to manage data processing tasks.
4. [Stage 3 Analysis Prompt](https://github.com/PublicDataWorks/verdad/blob/main/prompts/Stage_3_analysis_prompt.md) - A specific prompt used in the analysis stage of the VERDAD project.
5. [YouTube Interview with Rajiv Sinclair](https://www.youtube.com/watch?v=t_S-loWDGE0) - A video interview discussing the VERDAD project and its methodologies.
## Topics

![](topics/Tool/Gemini%201%205%20Flash)

![](topics/Tool/Gemini%20Pro)

![](topics/Tool/Whisper)

![](topics/Platform/Prefect)