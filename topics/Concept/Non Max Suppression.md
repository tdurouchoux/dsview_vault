---
type: Concept
---

Non-Max Suppression (NMS) is a post-processing technique used in object detection algorithms to filter out redundant bounding boxes. It works by selecting the bounding box with the highest confidence score and suppressing those that have a significant overlap with it, based on a predefined threshold. This process helps in reducing the number of duplicate detections and improving the accuracy of the detection results. NMS is particularly useful in applications like image localization and object detection, where multiple bounding boxes may be generated for the same object.