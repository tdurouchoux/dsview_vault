---
already_read: true
link: https://primeradiant.com/blog/2026/smevals.html
read_priority: 0
relevance: 2
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2026-08-24'
---

https://primeradiant.com/blog/2026/smevals.html

## Summary

smevals is a lightweight Python CLI tool for evaluating models, prompts, and harnesses to identify cost-effective small models for specific tasks.

**Core Concepts**
- An *eval* is a collection of tasks (e.g., "Generate an SVG of a pelican riding a bicycle") to test a model's capability.
- A *config* defines the model and parameters (e.g., system prompts, model settings) for evaluation.
- A *run* records the execution of a task under a specific config, executed by a *runner* script.
- A *grader* evaluates run outputs via checks (simple string checks, XML validation, or custom scripts).
- *Checkers* can use other models (e.g., GPT-5.5) to grade outputs (e.g., syllable counts, subject adherence).

**Workflow**
- Design tasks and grading logic, then run them against configs.
- Results can be viewed in-terminal or via a web app (static or dynamic).
- Example: `uvx smevals run . -g -m gpt-5.5 -m gpt-5.4-nano` runs tasks against two models and grades them.

**Key Features**
- Agent-friendly: README enables coding agents (e.g., Claude Code) to auto-generate evals.
- Modular: Separates running evals from grading, allowing regrading of existing runs.
- Web reports: Static or live reports for comparing model performance.
- Example checker: `haiku-judge` uses GPT-5.5 to validate syllable patterns (5-7-5) and subject adherence.

**Example Output**
- Grader checks for 3-line structure, syllable counts, and poetic quality (score 0–1).
- Static reports deployable via `uvx smevals build .`.

## Links

- [smevals GitHub Repository README](https://github.com/prime-radiant-inc/smevals/blob/main/README.md) : The official README for the smevals project, which provides detailed documentation on how to use the tool, including setup, configuration, and examples. This is highly relevant as it directly supports the content of the blog post, which introduces smevals and its features.
- [Static Report Example for Haiku Eval](https://static.simonwillison.net/static/2026/smevals-haiku-build/) : A static web report generated using smevals for the haiku evaluation example described in the blog post. This demonstrates the output format and capabilities of the tool, making it a valuable reference for users interested in visualizing eval results.


## Topics

![[topics/Library/smevals]]

![[topics/Tool/llm CLI]]

![[topics/Model/GPT]]

![[topics/Model/GPT 5 4 nano]]

![[topics/Model/gpt 4 1 mini]]

![[topics/Platform/OpenAI Codex]]

![[topics/Concept/Eval Suite]]

![[topics/Concept/Grader]]

![[topics/Concept/Checker]]

![[topics/Tool/Claude Code]]