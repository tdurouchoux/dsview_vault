---
already_read: false
link: https://www.deeplearning.ai/the-batch/noir-a-system-to-control-robots-via-electroencephalogram-for-everyday-tasks/
read_priority: 1
relevance: 0
source: null
tags:
- Computer_Vision
type: Content
upload_date: '2024-05-23'
---

https://www.deeplearning.ai/the-batch/noir-a-system-to-control-robots-via-electroencephalogram-for-everyday-tasks/
## Summary

NOIR is a system designed to control robots using electroencephalogram (EEG) signals for everyday tasks. Developed by Ruohan Zhang and colleagues at Stanford, NOIR enables users to perform complex actions by breaking them down into simple thoughts, such as selecting an object, choosing an action, and specifying a location. The system uses EEG signals to train user-specific Quadratic Discriminant Analysis (QDA) classifiers. Users wear EEG electrodes and concentrate on specific sequences of thoughts to execute tasks while watching a screen displaying the robot's camera feed. The system uses OWL-ViT for object segmentation and flickering to help users select objects. Once an object is selected, the system presents possible actions, and users imagine using specific body parts to select an action. For location selection, users control a cursor using imagined hand movements or focusing on a cross. The system also includes an R3M embedding model to suggest commonly selected objects and actions. In tests, three users controlled two robots to execute 20 everyday tasks, with average accuracies of 81.2% for object selection, 42.2% for action selection, and 73.9% for location selection. The system demonstrates that simple statistical techniques can effectively decode complex brain signals for practical applications.
## Links

- [Quadratic Discriminant Analysis](https://en.wikipedia.org/wiki/Quadratic_classifier?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) : Wikipedia page about Quadratic Discriminant Analysis, a statistical method used to classify objects into different categories based on their features.
- [Franka Robotics](https://franka.de/?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) : Website of Franka Robotics, a company that designs and manufactures robotic arms for research and industrial applications.
- [Tiago Robot](https://pal-robotics.com/robots/tiago/?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE) : Website of PAL Robotics, a company that designs and manufactures humanoid robots for research and service applications. The Tiago robot is a humanoid robot designed for research and service applications.

## Topics

![](topics/Concept/Neural%20Signal%20Operated%20Intelligent%20Robots%20NOIR)

![](topics/Model/OWL%20ViT)

![](topics/Model/R3M)

![](topics/Concept/Quadratic%20Discriminant%20Analysis%20QDA)