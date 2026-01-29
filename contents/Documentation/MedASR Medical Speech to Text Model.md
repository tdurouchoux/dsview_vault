---
already_read: true
link: https://developers.google.com/health-ai-developer-foundations/medasr
read_priority: 0
relevance: 4
source: null
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2026-01-29'
---

https://developers.google.com/health-ai-developer-foundations/medasr
## Summary

MedASR is a speech-to-text model based on the Conformer architecture, pre-trained for medical dictation and transcription. It was trained on 5,000 hours of de-identified medical speech across various specialties. The model accepts mono-channel audio and generates text-only transcriptions, excelling in specialized medical terminologies.

Key features and use cases include:

- **Medical Dictation and Transcription**: Suitable for radiology dictation and clinical documentation.
- **Fine-tuning for Specialized Contexts**: Can be adapted for specific accents, acoustic environments, vocabulary expansion, and formatting.
- **Generative AI Integration**: Can be used with models like MedGemma for tasks such as generating SOAP notes or summarizing patient visits.

The model is intended for developers to build healthcare-based voice applications, with guidelines and resources provided for getting started and fine-tuning.
## Links

- [Quick start notebook](https://colab.research.google.com/github/google-health/medasr/blob/main/notebooks/quick_start_with_hugging_face.ipynb) : A notebook to try running the model locally.
- [Fine-tuning notebook](https://colab.sandbox.google.com/github/google-health/medasr/blob/main/notebooks/fine_tune_with_hugging_face.ipynb) : A notebook to fine-tune MedASR on your own data.

## Topics

![[topics/Model/MedGemma]]

![[topics/Concept/Conformer architecture]]

![[topics/Model/MedASR]]