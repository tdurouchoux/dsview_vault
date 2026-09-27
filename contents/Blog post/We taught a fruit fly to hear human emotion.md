---
already_read: true
link: https://oruk.ai/research/we-taught-a-fruit-fly-to-read-human-emotion
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Natural_Language_Processing
- Deep_Learning
type: Content
upload_date: '2026-09-27'
---

https://oruk.ai/research/we-taught-a-fruit-fly-to-read-human-emotion

## Summary

A research team repurposed a fruit fly’s neural wiring as a fixed recurrent network to classify human emotional speech, showing that biological structure alone may not outperform random connectivity for this task.

**Core experiment**
- 499 neurons from a fruit fly’s central brain were modeled with 15,865 directed connections (867,344 synaptic contacts).
- Neurotransmitter signs (ACh positive, GABA/glutamate negative) and connection weights scaled by log(1 + contact count).
- Input: 32 log-mel audio bands (8 kHz, 25 ms window, 10 ms hop), projected into the circuit every 10 ms.
- Output: linear readout trained on 15 emotion labels + 16 speaking styles, with direct pooled audio features as a parallel input.

**Performance & controls**
- Test set: 2,022 clips; metric: mean average precision (mAP) across 31 labels.
- Fly-wired model: 16.84% mAP; scrambled-wiring model: 16.88% mAP (Δ = −0.04%, 95% CI [−0.16, +0.07]).
- Audio-only baseline: 9.71% mAP; constant predictor: 9.71%.
- Silencing 50 highest-weight neurons drops mAP from 16.91% to 10.83% in a single trained model.

**Key takeaways**
- Reservoir computing approach: fixed fly circuit, only readout trained.
- No evidence fly’s specific wiring improves emotion classification over random connectivity.
- Model leverages temporal dynamics (recurrent activity) but biological structure offers no measurable advantage here.
- Interactive demos visualize neuron activity and lesion effects, but results are constrained by single-circuit, single-label-per-clip setup.

## Links

- [MaleCNS v1.0 Fly Brain Connectome Dataset](https://male-cns.janelia.org/download/) : The MaleCNS v1.0 dataset provides connection tables and reconstructed neuron shapes for the fruit fly's central brain, which was used in the experiment to model the neural circuit. This dataset is critical for replicating or studying the biological wiring of the fly brain.
- [CREMA-D Dataset for Emotional Speech](https://github.com/CheyneyComputerScience/CREMA-D) : The CREMA-D dataset contains 21,256 distinct waveforms of emotional speech, which was used as part of the training and evaluation data for the experiment. It includes recordings labeled with emotions, making it a key resource for speech emotion recognition research.
- [conn2res: Reservoir Computing with Biological Connectomes](https://www.nature.com/articles/s41467-024-44900-4) : This Nature Communications article discusses the application of reservoir computing using biological connectomes (like the fruit fly brain) for time-series prediction tasks. It provides theoretical and methodological context for the experiment described in the content.
- [Fruit Fly Connectome for Time-Series Prediction (Costi et al., 2025)](https://www.mdpi.com/2313-7673/10/5/341) : This MDPI article explores the use of a fruit fly connectome for time-series prediction, which is directly relevant to the experiment's approach of using a fixed recurrent neural network derived from a fly's brain to process human speech.


## Topics

![[topics/Library/conn2res]]

![[topics/Model/Resonance 2]]

![[topics/Dataset/CREMA D]]

![[topics/Dataset/VCTK]]

![[topics/Platform/Oruk]]

![[topics/Concept/Reservoir Computing]]

![[topics/Concept/Connectome]]

![[topics/Concept/Synaptic Contacts]]