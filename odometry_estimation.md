---
layout: default
title: Odometry Estimation
---

# Multimodal Off-Road Odometry for Robust Localization

### Overview
This challenge aims to address one of the core difficulties in off-road autonomy: estimating vehicle odometry in environments where traditional GPS-based methods may be unreliable or degraded. Participants must use multimodal sensor data to estimate the vehicle’s trajectory while overcoming challenges such as sensor noise, GPS dropouts, and rough, unpredictable terrain.

### Task Details
Participants are tasked with developing algorithms that fuse multiple sensor modalities to accurately estimate vehicle odometry in off-road environments. The dataset includes synchronized data from various sensors:
- **RGB Cameras**: For visual odometry and terrain recognition.
- **LiDAR**: For detecting the vehicle’s surroundings and mapping terrain structure.
- **RADAR**: For understanding the environment in adverse conditions (e.g., fog, dust).
- **Thermal**: To capture the heat signatures of the environment.
- **IMU and GPS**: While GPS data will be included, some portions of the dataset will simulate degraded GPS signals, forcing participants to rely on other sensor data.

Participants can explore techniques like:
- **Sensor Fusion Algorithms**: Combining data from multiple sources to improve odometry accuracy, especially in GPS-denied areas.
- **Deep Learning for Odometry**: Learning-based methods to estimate trajectory from sensor data.
- **SLAM (Simultaneous Localization and Mapping)**: Developing or adapting SLAM algorithms to off-road environments where terrain features are less structured.

### Dataset
Participants will have access to:
- Multimodal sensor data collected from off-road environments such as rocky paths, forest trails, and sandy dunes.
- Synchronized data streams from all sensors to enable efficient fusion and localization.

### Evaluation Metrics
The submissions will be evaluated based on:
- **Root Mean Square Error (RMSE)**: Measures the accuracy of the estimated trajectory relative to the ground truth.
- **Absolute Trajectory Error (ATE)**: Assesses the global consistency of the estimated trajectory.
- **Robustness**: Includes failure rate, where participants' algorithms will be tested on segments with GPS dropouts or sensor noise.
- **Efficiency**: Computational efficiency, including processing time and CPU/GPU utilization.

---

Participants are encouraged to explore unconventional approaches and leverage recent advancements in machine learning and sensor fusion techniques. Awards will be given based on performance in accuracy, robustness, and innovation.

Good luck, and we look forward to seeing your submissions!
