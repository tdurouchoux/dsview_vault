---
already_read: true
link: https://www.worldlabs.ai/blog/atlas
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Computer_Vision
type: Content
upload_date: '2026-09-26'
---

https://www.worldlabs.ai/blog/atlas

## Summary

Atlas is a new omni world model for spatial intelligence that natively operates on text, images, video, and 3D to generate, reconstruct, and simulate worlds with high fidelity.

**Overview**
- Multimodal autoregressive diffusion transformer combining text, images, video, and 3D inputs into a shared spatial context.
- Performance scales with increased training compute.

**Capabilities**
- **Camera-Controlled Generation:** Generates images/videos from 1-6 input images with pixel-perfect camera control (up to 1440p, 1-minute videos).
- **Spatial Reconstruction:** Reconstructs 3D scenes from 1 to >100 input images, outperforming specialized 3D reconstruction models.
- **Space-Time Simulation:** Reframes videos for VFX and enables Real-to-Sim workflows for robotics.
- **Image Generation:** Produces images and 360 panoramas from text, handling complex prompts and styles.

**Technical Details**
- **Model Architecture:** Multimodal autoregressive diffusion transformer with spatial context grounding.
- **Inputs:** Text, images, camera poses, 3D depth maps (videos as image sequences).
- **Outputs:** 2D images/videos, 3D point clouds, or Gaussian splats.
- **Scaling:** Pretrained from scratch; larger models show improved capabilities.

**Benchmarks**
- **Camera-Controlled Generation:** Outperforms top video models (e.g., FLUX 3, Seedance 2.5) in human-rated camera path adherence.
- **3D Reconstruction:** Lower error than specialized models (e.g., Pi3X, π³VGG) across DTU, ETH3D, KITTI, and other datasets.

**Applications**
- Creative tools (Marble integration), robotics simulation, VFX, and design workflows.

## Links

- [Marble Platform](https://marble.worldlabs.ai/) : The official platform page for Marble, a product powered by Atlas. This link likely provides access to demonstrations, documentation, or early access requests for Marble, which is a spatial intelligence application built on Atlas.
- [World Labs SparkJS](https://sparkjs.dev/) : Documentation and resources for SparkJS, a tool or library developed by World Labs. Given the context of Atlas, this could be related to spatial intelligence, 3D modeling, or multimodal data processing tools.
- [World Labs Careers](https://www.worldlabs.ai/careers) : The careers page for World Labs, detailing job opportunities and roles in research, engineering, and other fields. This is relevant for professionals interested in contributing to spatial intelligence and world modeling technologies like Atlas.


## Topics

![[topics/Model/Atlas]]

![[topics/Platform/World Labs]]

![[topics/Concept/Spatial Intelligence]]

![[topics/Concept/World Models]]

![[topics/Concept/Multimodal Autoregressive Diffusion Transformer]]

![[topics/Concept/Real to Sim]]

![[topics/Dataset/DTU]]

![[topics/Dataset/ETH3D]]

![[topics/Dataset/KITTI]]