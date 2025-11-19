# unified-3d-segmentation-transformer
# OneFormer3D: Unified 3D Point Cloud Segmentation Transformer

## Overview
OneFormer3D is a state-of-the-art framework designed for unified 3D point cloud segmentation. It simultaneously tackles **semantic segmentation**, **instance segmentation**, and **panoptic segmentation** using a transformer-based architecture, allowing for multi-task learning in a single end-to-end model.

This repository aims to replicate and implement the **OneFormer3D** model, which sets a new benchmark in 3D segmentation tasks by achieving top-tier performance on datasets such as **ScanNet**, **ScanNet200**, and **S3DIS**.

## Key Features
- **Multi-task segmentation**: Performs 3D semantic, instance, and panoptic segmentation tasks jointly.
- **Transformer-based architecture**: Utilizes a transformer decoder with both semantic and instance queries.
- **State-of-the-art results**: Achieves top rankings in the ScanNet test leaderboard and other key benchmarks.

## Objectives
- **Reproduce the OneFormer3D model** using PyTorch and relevant frameworks.
- **Achieve state-of-the-art results** on popular 3D segmentation benchmarks.
- **Explore transformer-based methods** for efficient and accurate 3D point cloud segmentation.

## Setup
### Requirements
- Python >= 3.8
- PyTorch >= 1.10.0
- MMDetection3D
- MMSegmentation

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/oneformer3d.git
   cd oneformer3d
