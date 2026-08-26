---
already_read: false
link: https://www.jagged-judges.com/paper
read_priority: 4
relevance: 0
source: alliance
tags:
- Large_Language_Model
- Model_evaluation
type: Content
upload_date: '2026-08-26'
---

https://www.jagged-judges.com/paper

## Summary

The Wiggle Framework reveals that LLM judges often flip their verdicts under pressure, with flips usually degrading accuracy rather than improving it.

**Core findings**
- Every tested model (9 frontier LLMs) wiggles substantially as a judge, flipping 25–71% under static pushback and 62–91% with an adversarial LLM persuader.
- Pressure that changes a judge's verdict is almost always net-corrupting (56–70% of flips move away from ground truth).
- Mechanical Consistency (re-prompting/reframing) shows minimal wiggle (2–9%), but Single-turn Conviction and Multi-turn Persistence reveal severe instability.

**Framework dimensions**
- **Mechanical Consistency**: Stability under semantically invariant perturbations (repetition, seed injection, argument reordering).
- **Single-turn Conviction**: Stability under one challenge (mild doubt, counterargument, expert authority, fabricated consensus).
- **Multi-turn Persistence**: Stability under sustained/adaptive pressure (10-turn rollouts, cycling tactics, or adaptive LLM persuader).

**Key patterns**
- Binary scales flip more restrictively; Likert scales drift permissively.
- L4 (fabricated consensus) has the strongest opening wiggle, but L6 (adaptive persuasion) surpasses it over time.
- Baseline jury majority strength is the best predictor of item-level wiggle (median |ρ| = 0.58).

**Model/dataset insights**
- Wiggle profiles are model-specific but transfer poorly across datasets in absolute terms.
- MAGE (AI-text detection) is the most wiggly domain; ToxiGen (toxicity) is among the least.
- Family membership weakly predicts behavior; self-persuasion asymmetry exists (e.g., Claude Opus persuades itself best, Grok Reasoning worst).

**Implications**
- One-shot accuracy is insufficient for validating LLM judges; stability under pressure matters.
- Corruptive flips dominate, raising concerns for deployment in agentic systems.
- Cheap predictors (e.g., jury majority) can flag unstable items without full stress testing.

## Links

- [arXiv:2608.12645 - Jagged Judges: Epistemic Stability Under Silence, Pressure, and Persistence](https://arxiv.org/abs/2608.12645) : The primary research paper discussed in the content, introducing the Wiggle Framework for evaluating epistemic stability in LLM judges under various pressures. This is the most directly relevant link as it is the source of the study's findings and methodology.
- [arXiv:2403.04132 - Measuring Model Persuasiveness](https://arxiv.org/abs/2403.04132) : A related work cited in the paper, focusing on measuring the persuasiveness of models, which aligns with the Multi-turn Persistence dimension of the Wiggle Framework.
- [arXiv:2312.09085 - The FlipFlop Experiment: Measuring Sycophancy in LLMs](https://arxiv.org/abs/2312.09085) : A foundational study on sycophancy in LLMs, referenced in the paper to discuss single-turn challenges and their impact on judge stability.
- [arXiv:2406.18495 - Evaluating LLM-as-a-Judge in Benchmarks](https://arxiv.org/abs/2406.18495) : A study cited in the paper that evaluates the use of LLMs as judges in benchmarks, relevant to the broader context of LLM judge reliability and biases.
- [arXiv:2505.13995 - On the Calibration of Confidence in LLMs](https://arxiv.org/abs/2505.13995) : A paper cited in the content discussing the calibration of confidence in LLMs, which is directly related to the Mechanical Consistency and Conviction dimensions of the Wiggle Framework.


## Topics

![[topics/Concept/Wiggle Framework]]

![[topics/Concept/AI Robustness and Resilience]]

![[topics/Concept/LLM as Judge]]

![[topics/Model/GPT]]

![[topics/Model/Claude Opus]]

![[topics/Model/Grok 4 1 Reasoning]]

![[topics/Dataset/WildGuard]]

![[topics/Dataset/ToxiGen]]

![[topics/Dataset/MAGE]]

![[topics/Concept/Sycophancy]]