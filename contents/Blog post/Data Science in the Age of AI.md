---
already_read: true
link: https://www.robinlinacre.com/data_science_age_ai/
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2026-09-27'
---

https://www.robinlinacre.com/data_science_age_ai/

## Summary

The rise of LLMs has fundamentally transformed data science work, shifting the focus from coding to guiding AI with strong feedback loops to ensure reliable, high-quality outputs.

**Key shifts in data science**
- Day-to-day work now centers on steering AI agents rather than writing code.
- Feedback loops are critical to mitigating hallucinations and slop, turning reliability into a skill-based outcome.
- Core data science skills (judgement, problem translation, and recognizing "good" solutions) remain unchanged.

**Feedback loops in practice**
- Agents autonomously generate task-specific evidence (e.g., profiling, benchmarking) and verify progress.
- Stronger feedback loops enable delegation of larger, more complex tasks.

**Real-world examples**
- **Code profiling**: Agent achieved a 25% speedup in Splink with 15 lines of code, verified via test suite passage.
- **Version upgrades**: Agent upgraded Splink v4 examples to v5 by summarizing PR changes, verified by output consistency.
- **Code porting**: Agent ported DoubleMetaphone (Java→C++) and Splink (Python→WASM), verified via test suites and exact output matching.
- **Game balancing**: Agent played 1,000 self-simulated games to balance 7 gun types, adjusting only damage constants.
- **Semi-autonomous research**:
  - Developed a new "sounds-like" function outperforming Soundex (but not DoubleMetaphone) using rule-based ML.
  - Improved `uk_address_matcher` accuracy via "distinguishing tokens," verified by benchmarking and human review.
- **Human-in-the-loop**: Cursive handwriting required human verification tools (e.g., curve editors) to compensate for LLM weaknesses.

**Future trends**
- Cloud/always-on agents will enable longer-running, autonomous tasks (e.g., bug triage, model optimization).
- Agents will improve at memory/context management and intent recognition.
- Data scientists will manage teams of agents, accelerating delivery expectations.

**Big-picture takeaway**
- Value shifts to creativity, judgement, and tightening customer feedback loops to deliver faster, more valuable solutions.

## Links

- [Understanding ChatGPT Work](https://simonwillison.net/2026/Aug/30/understanding-chatgpt-work/) : A detailed post by Simon Willison discussing the evolution of AI tools like ChatGPT Work, which are designed to assist with coding and agentic workflows, aligning with the themes of AI-driven development discussed in the blog post.
- [AI Zealotry: Feedback Loops in AI Development](https://matthewrocklin.com/ai-zealotry/#feedback) : A post by Matthew Rocklin that explores the importance of feedback loops in AI-driven development, a key concept highlighted in the blog post regarding the role of data scientists in guiding AI solutions.
- [Splink in the Browser (DuckDB WASM)](https://www.robinlinacre.com/splink_in_browser/) : A demonstration of porting the Splink library to the web browser using DuckDB WASM, showcasing the agentic capabilities of AI in transforming and deploying data science tools across platforms.
- [uk_address_matcher Pull Request #444](https://github.com/moj-analytical-services/uk_address_matcher/pull/444) : A pull request demonstrating the use of AI to improve the accuracy of the uk_address_matcher geocoder by implementing new features and data cleaning rules, as discussed in the blog post.
- [Splink Pull Request #3162](https://github.com/moj-analytical-services/splink/pull/3162) : A pull request showcasing the upgrade of Splink from version 4 to version 5, highlighting the agentic work of automating code and documentation updates, as described in the blog post.


## Topics

![[topics/Platform/DuckDB WASM]]

![[topics/Library/Apache Commons]]

![[topics/Model/DoubleMetaphone]]

![[topics/Concept/Feedback Loops]]

![[topics/Concept/Semi autonomous research]]

![[topics/Library/Splink]]

![[topics/Library/DuckDB]]

![[topics/Concept/Human in the Loop]]