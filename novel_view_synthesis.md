---
layout: default
title: Novel View Synthesis
---

# Novel View Synthesis (NVS) for Off-Road Scenes

### Overview
Novel View Synthesis (NVS) is a crucial task in 3D scene reconstruction, especially in unstructured off-road environments where a complete understanding of the scene is necessary for autonomous navigation. In this challenge, participants are tasked with reconstructing a series of off-road scenes from partial image sequences, filling in missing frames and synthesizing accurate novel views.

### Task Details
Participants must generate missing frames for off-road environments, accurately reconstructing the scene from incomplete data. The dataset contains scenes captured during driving sequences with varying levels of difficulty based on the frame drop rate:
- **Level 1 (50% Frame Drop Rate)**: For each scene (approx. 50 meters of driving distance), participants will be provided with only 50% of the image frames, while the remaining 50% will be reserved for evaluation.
- **Level 2 (90% Frame Drop Rate)**: For each scenes (approx. 50 meters), only 10% of the frames will be provided, making it more challenging to reconstruct the complete scene.

Participants can use techniques like:
- **Neural Radiance Fields (NeRF)**: To synthesize novel views by learning the 3D geometry and appearance of the off-road scenes.
- **Multiview Geometry**: To infer missing frames based on the available sequence.
- **Deep Learning**: Using neural networks to learn the correlation between the provided frames and the missing frames.

### Dataset
The dataset includes:
- **RGB Images & LiDAR Point Clouds**: The data provides both image sequences and point clouds to assist in reconstructing the scenes.

### Submission: 
Participants will submit their synthesized frames for both levels, along with a brief report detailing their approach, including any innovative techniques used to handle the high frame drop rates.

### Evaluation Metrics
Participants’ submissions will be evaluated based on:
- **Peak Signal-to-Noise Ratio (PSNR)**: Measures the quality of the reconstructed frames relative to the original.
- **Structural Similarity Index (SSIM)**: Assesses the structural fidelity and perceived quality of the synthesized images.
- **Learned Perceptual Image Patch Similarity (LPIPS)**: Evaluates how close the synthesized images are to human visual perception.

