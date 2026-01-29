---
already_read: true
link: https://research.google/blog/next-generation-medical-image-interpretation-with-medgemma-15-and-medical-speech-to-text-with-medasr/
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- Natural_Language_Processing
- Computer_Vision
type: Content
upload_date: '2026-01-29'
---

https://research.google/blog/next-generation-medical-image-interpretation-with-medgemma-15-and-medical-speech-to-text-with-medasr/
## Summary

The content discusses advancements in medical AI, focusing on two main updates: MedGemma 1.5 and MedASR.

**MedGemma 1.5 4B** is an updated open medical generative AI model that enhances support for various medical imaging modalities, including high-dimensional imaging (CT, MRI, histopathology), longitudinal imaging (chest X-ray time series), anatomical localization, and medical document understanding. It also improves accuracy for text, medical records, and 2D images. The model is designed to be a starting point for developers to adapt for specific medical use cases and can be scaled on Google Cloud through Vertex AI. MedGemma 1.5 4B shows significant performance improvements over its predecessor, MedGemma 1 4B, in various benchmarks.

**MedASR** is a new open automated speech recognition (ASR) model fine-tuned for medical dictation. It converts medical speech to text and can be used in conjunction with MedGemma for advanced reasoning tasks. MedASR demonstrates superior performance compared to generalist ASR models, with fewer errors in medical dictation tasks.

The content also announces the **MedGemma Impact Challenge**, a hackathon with $100,000 in prizes, encouraging developers to explore creative uses of MedGemma models in healthcare.

Additionally, the post highlights real-world applications of MedGemma, such as its use in Malaysia's clinical practice guidelines and preoperative assessments for lung cancer surgery in Taiwan. It provides resources for developers, including tutorials and access to the models via Hugging Face and Vertex AI.

The content concludes with a disclaimer emphasizing that the models are not intended for direct clinical use without appropriate validation and adaptation. It also acknowledges the collaborative efforts behind the development of MedGemma and MedASR.
## Links

- [MedGemma 1.5 4B Model on Hugging Face](https://huggingface.co/google/medgemma-1.5-4b-it) : Access the MedGemma 1.5 4B model on Hugging Face for medical image interpretation and text tasks.
- [MedASR Model on Hugging Face](https://huggingface.co/google/medasr) : Access the MedASR model on Hugging Face for medical speech-to-text tasks.
- [MedGemma GitHub Repository](https://github.com/Google-Health/medgemma/tree/main/notebooks) : Explore tutorials and notebooks for using MedGemma models on GitHub.
- [MedGemma Impact Challenge on Kaggle](https://www.kaggle.com/competitions/med-gemma-impact-challenge) : Participate in the MedGemma Impact Challenge hackathon with $100,000 in prizes.

## Topics

![[topics/Model/MedGemma]]

![[topics/Model/MedASR]]

![[topics/Concept/High dimensional medical imaging]]

![[topics/Concept/Longitudinal medical imaging]]

![[topics/Concept/Anatomical localization]]

![[topics/Concept/Medical document understanding]]