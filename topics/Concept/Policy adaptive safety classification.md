---
type: Concept
---

A paradigm in AI safety where models evaluate content based on dynamically supplied policies at inference time, rather than relying on fixed, pre-trained taxonomies of harm. This approach allows the same model to adapt to different deployment contexts, audiences, or regulatory requirements without retraining. Shieldstral exemplifies this by accepting plain-language policies (e.g., 'Does this content promote violence against a protected group?') and returning calibrated safety scores based on the provided policy.