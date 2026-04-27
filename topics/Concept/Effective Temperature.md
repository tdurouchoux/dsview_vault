---
type: Concept
---

Effective temperature (Teff) is a composite measure that combines the training-time temperature (Ttrain) and evaluation-time temperature (Teval) to describe their combined effect on the model's output distribution. In self-distillation, Teff governs the balance between precision and exploration, with higher values promoting diversity and lower values favoring precision. The relationship Teff = Ttrain * Teval highlights how training-time and evaluation-time temperatures interact multiplicatively to shape the model's behavior.