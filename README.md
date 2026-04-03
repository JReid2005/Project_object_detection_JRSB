# Project_object_detection_JRSB
Object detection workflow using NVIDIA Jetson Nano and GPU acceleration

## Problem Statement
Real-time object detection is one of the key AI tasks in use cases such as autonomous
vehicles, surveillance systems, robotics, and industrial automation. It allows to identify
and classify objects within images or video streams in real-time. AI inference tasks such
as object detection are computationally intensive. Research shows that a higher speed
up and lower latency can be achieved by using parallel hardware and optimized software
frameworks.
Traditionally, such inference tasks have been carried out on powerful cloud-based
servers. However, there is a growing demand for low-latency, high-throughput, and real-
time performance on embedded edge devices. Embedded devices with AI accelerators
provide a powerful compact platform for deploying machine learning inference. They
enable AI to run in diverse environments and applications closer to the user and on
premise.
How would you leverage the capabilities of an accelerator-enabled embedded edge
device for a real-time AI inferencing task such as object-detection?

## Hardware
- NVIDIA Jetson Nano
- Camera

## Software
- Python
- CUDA
- OpenCV
- PyTorch

## Object Detection Model
YOLOv5

## Techniques
- Brent-Kung scan algorithm

## Optimization Techniques
- Tiling
- Thread coarsening

## Repository Structure
Workflow/
Reflection/
code/
