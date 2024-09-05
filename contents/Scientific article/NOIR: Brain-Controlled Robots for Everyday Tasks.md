---
already_read: false
link: https://www.deeplearning.ai/the-batch/noir-a-system-to-control-robots-via-electroencephalogram-for-everyday-tasks/
read_priority: 1
source: null
type: Content
upload_date: '2024-05-23'
---

https://www.deeplearning.ai/the-batch/noir-a-system-to-control-robots-via-electroencephalogram-for-everyday-tasks/
## Summary

Researchers at Stanford have developed NOIR (Neural Signal Operated Intelligent Robots), a system that allows users to control robots for everyday tasks using electroencephalogram (EEG) signals. Unlike previous systems that focused on single tasks, NOIR can execute complex actions by interpreting sequences of simple thoughts, such as selecting an object and performing an action on it.

Key components of the system include:

- **EEG Training**: Users wear EEG electrodes and concentrate on specific thoughts to train the system, which involves imagining actions like grasping or pushing.
- **Object Selection**: A pretrained OWL-ViT model segments camera images to identify objects, which flicker at varying frequencies. Users focus on an object to select it based on synchronized brainwave patterns.
- **Action and Location Selection**: Users choose actions from presented options by imagining using specific body parts. A cursor helps select locations on the object, with movements controlled by imagined actions or focusing on a cross.
- **Error Correction**: Users can reset the selection process by clenching their jaw if the system misreads their intentions.

Results showed that users achieved an average of 81.2% accuracy in object selection, 42.2% in action selection, and 73.9% in location selection, completing tasks in about 20 minutes. The study highlights the potential of using simple statistical techniques, like Quadratic Discriminant Analysis, to decode complex brain signals effectively. The approach emphasizes breaking down complex tasks into manageable steps rather than relying solely on larger models.
## Links

1. [Neural Signal Operated Intelligent Robots (NOIR)](https://arxiv.org/abs/2311.01454?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - Research paper detailing the NOIR system for controlling robots using EEG signals.
2. [Quadratic Discriminant Analysis](https://en.wikipedia.org/wiki/Quadratic_classifier?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - Wikipedia page explaining the QDA technique used in the NOIR system for decoding brain signals.
3. [OWL-ViT](https://arxiv.org/abs/2205.06230?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - Research paper on the OWL-ViT model used for object segmentation in the NOIR system.
4. [R3M](https://arxiv.org/abs/2203.12601?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - Research paper discussing the R3M embedding model adapted for the NOIR system to suggest object-action combinations.
5. [Robotic Arm](https://franka.de/?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - Information about robotic arms, which are integral to the tasks performed by the NOIR system.
## Topics

- [[topics/Concept/Brain-Controlled Robots]]
- [[topics/Model/Quadratic Discriminant Analysis (QDA)]]
- [[topics/Model/R3M embedding model]]
- [[topics/Concept/Brain-to-Computer Interface]]