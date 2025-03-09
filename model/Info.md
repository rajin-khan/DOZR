# YOLOv5 Directory Structure

This document provides information about the files that belong in the YOLOv5 directory.

## dataset.yaml
- The `dataset.yaml` file must be placed in the YOLOv5 directory.
- This file contains the dataset configuration, including paths to training and validation datasets, class names, and other relevant information.

## Weight Files
- Weight files (e.g., `best.pt`, `last.pt`) should also be stored in the YOLOv5 directory.
- These files contain the trained model weights and are essential for running inference or resuming training.

## Other Files
- Any additional configuration files, scripts, or resources related to the YOLOv5 model should be kept in the same directory.
- "main" goes into yolov5, and renamed to runs/train/exp
- This ensures that all necessary components are organized and easily accessible for training and inference tasks.

By maintaining this directory structure, you can ensure that all required files for YOLOv5 are properly organized and readily available.
