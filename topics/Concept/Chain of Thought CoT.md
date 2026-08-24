---
type: Concept
---

A reasoning approach used in large language models where the model generates intermediate steps or 'thinking tokens' (Chains of Thought) before arriving at a final answer. This method breaks down complex tasks into smaller, more manageable steps to improve transparency, interpretability, and accuracy. CoT can be enabled via prompting techniques (e.g., 'think step by step') or as a core feature of LRMs. However, it may also lead to hallucinations or superficial reasoning chains that do not reflect the model's actual internal processes. CoT prompting increases inference cost due to additional output tokens but is particularly useful for tasks like puzzles or advanced math problems, and is foundational to frameworks like Graph of Thoughts.