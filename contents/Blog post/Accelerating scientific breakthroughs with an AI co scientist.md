---
already_read: false
link: https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist/
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2025-02-20'
---

https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist/
## Summary

The content introduces an AI co-scientist, a multi-agent AI system built with Gemini 2.0, designed to assist scientists in generating novel hypotheses and research proposals, and accelerating scientific and biomedical discoveries. The AI co-scientist system is intended to function as a collaborative tool for scientists, mirroring the reasoning process underpinning the scientific method. It uses a coalition of specialized agents — Generation, Reflection, Ranking, Evolution, Proximity, and Meta-review — that are inspired by the scientific method itself. These agents use automated feedback to iteratively generate, evaluate, and refine hypotheses, resulting in a self-improving cycle of increasingly high-quality and novel outputs.

The system is designed to parse the assigned goal into a research plan configuration, managed by a Supervisor agent. The Supervisor agent assigns the specialized agents to the worker queue and allocates resources. This design enables the system to flexibly scale compute and to iteratively improve its scientific reasoning towards the specified research goal.

The AI co-scientist leverages test-time compute scaling to iteratively reason, evolve, and improve outputs. Key reasoning steps include self-play–based scientific debate for novel hypothesis generation, ranking tournaments for hypothesis comparison, and an "evolution" process for quality improvement. The system's agentic nature facilitates recursive self-critique, including tool use for feedback to refine hypotheses and proposals.

The system's self-improvement relies on the Elo auto-evaluation metric derived from its tournaments. Due to their core role, we assessed whether higher Elo ratings correlate with higher output quality. We analyzed the concordance between Elo auto-ratings and GPQA benchmark accuracy on its diamond set of challenging questions, and we found that higher Elo ratings positively correlate with a higher probability of correct answers.

Seven domain experts curated 15 open research goals and best guess solutions in their field of expertise. Using the automated Elo metric we observed that the AI co-scientist outperformed other state-of-the-art agentic and reasoning models for these complex problems. The analysis reproduced the benefits of scaling test-time compute using inductive biases derived from the scientific method. As the system spends more time reasoning and improving, the self-rated quality of results improve and surpass models and unassisted human experts.

On a smaller subset of 11 research goals, experts assessed the novelty and impact of the AI co-scientist–generated results compared to other relevant baselines; they also provided overall preference. While the sample size was small, experts assessed the AI co-scientist to have higher potential for novelty and impact, and preferred its outputs compared to other models. Further, these human expert preferences also appeared to be concordant with the previously introduced Elo auto-evaluation metric.

To assess the practical utility of the system’s novel predictions, we evaluated end-to-end laboratory experiments probing the AI co-scientist–generated hypotheses and research proposals in three key biomedical applications: drug repurposing, proposing novel treatment targets, and elucidating the mechanisms underlying antimicrobial resistance. These settings all involved expert-in-the-loop guidance and spanned an array of complexities.

The AI co-scientist proposed novel repurposing candidates for acute myeloid leukemia (AML). Subsequent experiments validated these proposals, confirming that the suggested drugs inhibit tumor viability at clinically relevant concentrations in multiple AML cell lines.

The AI co-scientist demonstrated its potential by identifying epigenetic targets grounded in preclinical evidence with significant anti-fibrotic activity in human hepatic organoids (3D, multicellular tissue cultures derived from human cells and designed to mimic the structure and function of the human liver). These findings will be detailed in an upcoming report led by collaborators at Stanford University.

The AI co-scientist system independently proposed that cf-PICIs interact with diverse phage tails to expand their host range. This in silico discovery, which had been experimentally validated in the original novel laboratory experiments performed prior to use of the AI co-scientist system, are described in co-timed manuscripts (1, 2) with our collaborators at the Fleming Initiative and Imperial College London. This illustrates the value of the AI co-scientist system as an assistive technology, as it was able to leverage decades of research comprising all prior open access literature on this topic.

In our report we address several limitations of the system and opportunities for improvement, including enhanced literature reviews, factuality checking, cross-checks with external tools, auto-evaluation techniques, and larger-scale evaluation involving more subject matter experts with varied research goals. The AI co-scientist represents a promising advance toward AI-assisted technologies for scientists to help accelerate discovery. Its ability to generate novel, testable hypotheses across diverse scientific and biomedical domains — some already validated experimentally — and its capacity for recursive self-improvement with increased compute, demonstrate its potential to accelerate scientists' efforts to address grand challenges in science and medicine. We look forward to responsible exploration of the potential of the AI co-scientist as an assistive tool for scientists. This project illustrates how collaborative and human-centred AI systems might be able to augment human ingenuity and accelerate scientific discovery.

We are excited by the early promise of the AI co-scientist system and believe it is important to evaluate its strengths and limitations in science and biomedicine more broadly. To facilitate this responsibly we will be enabling access to the system for research organizations through a Trusted Tester Program. We encourage interested research organizations around the world to consider joining this program here.
## Links

- [AI co-scientist paper](https://storage.googleapis.com/coscientist_paper/ai_coscientist.pdf) : The AI co-scientist paper provides a detailed overview of the multi-agent AI system designed to assist scientists in generating novel hypotheses and research proposals, leveraging Gemini 2.0 for advanced scientific reasoning and collaboration.
- [Gene transfer discovery paper](https://storage.googleapis.com/coscientist_paper/penades2025ai.pdf) : This paper discusses the discovery of gene transfer mechanisms related to antimicrobial resistance, highlighting the AI co-scientist's ability to propose and validate novel scientific hypotheses through experimental validation.

## Topics

![](topics/Concept/AI%20Co%20Scientist)

![](topics/Concept/AI%20Agents)

![](topics/Model/Gemini)

![](topics/Concept/Scientific%20Method)

![](topics/Concept/Elo%20Auto%20Evaluation%20Metric)

![](topics/Concept/Inference%20time%20Scaling)

![](topics/Concept/Transdisciplinary%20Research)

![](topics/Concept/Drug%20Repurposing)

![](topics/Concept/Target%20Discovery)

![](topics/Concept/Antimicrobial%20Resistance)