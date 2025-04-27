---
already_read: false
link: https://www.deeplearning.ai/the-batch/noir-a-system-to-control-robots-via-electroencephalogram-for-everyday-tasks/
read_priority: 1
relevance: 0
source: null
tags:
- AI_agent
- Data_Engineering
type: Content
upload_date: '2024-05-23'
---

https://www.deeplearning.ai/the-batch/noir-a-system-to-control-robots-via-electroencephalogram-for-everyday-tasks/
## Summary

Researchers at Stanford have developed NOIR, a system enabling robots to be controlled through electroencephalogram (EEG) signals for performing complex everyday tasks, like ironing or making a sandwich. Unlike traditional brain-computer interfaces that handle simple tasks, NOIR interprets a series of simple intentions to execute more intricate actions.

The system works by first training on an individual's EEG signals as they concentrate on specific thoughts related to task execution. EEG recordings allowed the researchers to create classifiers that detect user intentions based on brainwave patterns. Users selected objects which flickered on a screen, with the system identifying the chosen object based on the synchronized brainwaves. After object selection, users could choose an action from multiple options, again using thought patterns interpreted by the EEG data.

Results showed that users were able to control the robots with varying accuracy: object selection at 81.2%, action selection at 42.2%, and location selection at 73.9%. The average time taken to complete tasks was about 20 minutes. This work highlights the potential for simpler statistical methods, like Quadratic Discriminant Analysis, to decode complex brain signals effectively, emphasizing that breaking down complex tasks into smaller steps can yield practical solutions.
## Links

- [Quadratic Classifier - Wikipedia](https://en.wikipedia.org/wiki/Quadratic_classifier) : An overview of quadratic classifiers, including their mathematical foundations and applications in machine learning.
- [arXiv: Brain-Controlled Robots](https://arxiv.org/abs/2205.06230) : A research paper detailing advancements in brain-controlled robotic systems and their applications.
- [arXiv: Electroencephalogram Based Control](https://arxiv.org/abs/2203.12601) : Research discussing the use of EEG signals to control robots and the methodologies involved.
- [R3M: Reinforcement Learning for Robots](https://arxiv.org/abs/2311.01454) : A paper on the R3M embedding model, used for robot training based on camera input and actions accepted.
- [PAL Robotics - TIAGo Robot](https://pal-robotics.com/robots/tiago/) : Information on TIAGo, a robot designed for various tasks of interaction and manipulation, relevant to control systems.

## Topics

![](topics/Concept/Brain%20Controlled%20Interface)

![](topics/Tool/Quadratic%20Discriminant%20Analysis%20QDA)

![](topics/Model/R3M%20Model)

![](topics/Concept/Electroencephalography%20EEG)

![](topics/Concept/Robot%20Task%20Execution)