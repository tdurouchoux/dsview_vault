---
already_read: true
link: https://github.com/metabase/dataset-generator
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2025-09-17'
---

https://github.com/metabase/dataset-generator
## Summary

The AI Dataset Generator by Metabase is a tool designed to create realistic datasets for demos, learning, and dashboards. It offers a conversational prompt builder to define business types, schemas, and other parameters. Key features include real-time data preview, export options (CSV or SQL), and one-click Metabase launch for data exploration.

The tool uses a two-stage process: first, it leverages large language models (LLMs) to generate detailed data specifications, and then it uses these specifications to create realistic data locally using Faker.js. The cost is incurred only during the preview stage, with subsequent downloads being free.

Prerequisites include Node.js (18 or later), an OpenAI API key, and optionally Docker for Metabase and multi-provider LLM support. The project structure includes components for the main UI, data generation, Docker orchestration, and export logic. The stack comprises Next.js, Tailwind CSS, LiteLLM, Faker.js, and Metabase.

To extend or contribute, users can add new business types by editing the spec-prompts.ts file. The project is open-source under the MIT license.
## Links

- [Metabase Documentation](https://www.metabase.com/docs/latest/exploration-and-organization/uploads) : Metabase documentation on uploading data for analysis.
- [Docker Get Started](https://www.docker.com/get-started) : Guide to getting started with Docker, which is used for running Metabase in this project.

## Topics

![](topics/Tool/AI%20Dataset%20Generator)

![](topics/Library/Faker%20js)

![](topics/Platform/Metabase)

![](topics/Library/LiteLLM)