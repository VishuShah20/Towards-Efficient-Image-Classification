# Modified ResNet for CIFAR-10 Classification

## Overview

This repository contains the implementation of a modified Residual Network (ResNet) designed to achieve high image classification accuracy on the CIFAR-10 dataset with the constraint of having no more than 5 million trainable parameters. This project is part of a deep learning mini-project aimed at creating efficient image classification models that are suitable for devices with limited storage capacity, such as wearable technology.

## Use Case

The model is specifically optimized for scenarios where high accuracy is required without the luxury of extensive computational resources. It's ideal for embedded systems or portable devices where model size and speed are crucial.

## Model Details

- **Architecture**: The model is a streamlined version of the classic ResNet architecture. It uses fewer parameters by adjusting the number of channels, filter sizes, and the architecture of residual blocks.
- **Parameters**: The model consists of approximately 4.78 million trainable parameters.
- **Accuracy**: Achieves a test accuracy of 91.72% on the CIFAR-10 dataset.

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch 1.8+
- torchvision 0.9+
- CUDA (Optional for GPU acceleration)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anuj3509/DL-Mini-Project.git
