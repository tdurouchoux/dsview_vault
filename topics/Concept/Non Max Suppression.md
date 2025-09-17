---
type: Concept
---

Non-Max Suppression (NMS) is a technique used in object detection and other computer vision tasks to filter out redundant bounding boxes and improve the accuracy of the detection results. It works by sorting the bounding boxes in order of confidence scores and then suppressing those that have a high overlap with the highest-confidence detection. NMS is often implemented as a layer in deep learning models and can be challenging to optimize and port to different hardware platforms due to its procedural nature.