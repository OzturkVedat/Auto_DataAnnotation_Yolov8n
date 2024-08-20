# Automating Data Annotation with YOLOv8n 🚀

## Overview

This project aims to train a mini CNN model using a limited dataset (e.g. ~1k samples across 2 classes). The goal is to maximize detection efficiency so that the automated data annotation pipeline can accurately label new data, which will soon be fed into a larger CNN model.

## Features

- Implements YOLOv8n for high-accuracy object detection with a limited dataset.
- Applies data augmentation and non-max suppression for better performance.
- Automates data annotation for training of larger models.
- Configurable dataset setup with `data.yaml`.
- Includes a Jupyter Notebook for training and evaluation.

## Pre-requisites

### Hardware
- **CPU**: Multi-core processor recommended.
- **GPU**: NVIDIA GPU with CUDA support (e.g., GTX 1650 or better) for faster training.
- **RAM**: 8GB or more.

### Software
- **Python**: Version 3.7+.
  
### Dependencies
- **Python Packages**:
  - `ultralytics` (YOLOv8)
  - `opencv-python`
  - `numpy`
  - `matplotlib` (optional)
 
## Setting Up

1. Clone the repository:
   ```bash
   git clone https://github.com/OzturkVedat/Auto_DataAnnotation_Yolov8n
   cd Auto_DataAnnotation_Yolov8n

2. Configure:
  Edit `data.yaml` for your dataset and class names.

4. Run:
  Open the Jupyter Notebook file (*.ipynb) and execute the cells to train and evaluate the model as needed.   
