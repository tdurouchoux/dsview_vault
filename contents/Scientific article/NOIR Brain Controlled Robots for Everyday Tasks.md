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

Researchers at Stanford have developed NOIR (Neural Signal Operated Intelligent Robots), a system that allows users to control robots for everyday tasks using electroencephalogram (EEG) signals. Unlike previous brain-computer interfaces that focused on single tasks, NOIR can execute complex actions by interpreting sequences of simple thoughts.

Key points include:

- **Functionality**: Users can command robots to perform tasks like ironing or making a sandwich by concentrating on specific thought sequences. The system translates these thoughts into actions through a series of steps: selecting an object, choosing an action, and determining the action's location on the object.

- **Training Process**: Users undergo a 10-minute training session where their EEG signals are recorded while they imagine various movements. This data is used to train Quadratic Discriminant Analysis (QDA) classifiers tailored to each user.

- **Object and Action Selection**: The system employs a pretrained OWL-ViT model to identify objects on a screen, which flicker at specific frequencies. Users select objects by focusing on the corresponding flicker. Actions are chosen by imagining the use of specific body parts.

- **Accuracy and Performance**: In trials, users achieved an average object selection accuracy of 81.2%, action selection accuracy of 42.2%, and location selection accuracy of 73.9%. Each task took about 20 minutes to complete.

- **Implications**: The study highlights the potential of using simple statistical techniques to decode complex brain signals, suggesting that breaking down tasks into manageable steps can be more effective than relying solely on larger models.
## Links

1. [Quadratic classifier](https://en.wikipedia.org/wiki/Quadratic_classifier?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - Overview of quadratic classifiers, which are used in the NOIR system for decoding EEG signals.
2. [Neural Signal Operated Intelligent Robots (NOIR) Research Paper](https://arxiv.org/abs/2311.01454?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - The research paper detailing the NOIR system and its applications in brain-controlled robotics.
3. [R3M: A Robot Learning Model](https://arxiv.org/abs/2205.06230?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - A paper discussing the R3M embedding model used in the NOIR system for suggesting object-action combinations.
4. [TIAGo Robot](https://pal-robotics.com/robots/tiago/?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) - Information about the TIAGo robot, which is relevant to the context of robotic applications discussed in the article.
5. [Machine Learning and Data Science Specialization](https://www.deeplearning.ai/courses/mathematics-for-machine-learning-and-data-science-specialization/) - A course that covers foundational concepts in machine learning, which are essential for understanding the techniques used in the NOIR system.
## Topics

![](topics/Concept/Brain%20Controlled%20Robots)

![](topics/Product/NOIR)

![](topics/Model/R3M)

![](topics/Concept/Brain%20to%20Computer%20Interface)