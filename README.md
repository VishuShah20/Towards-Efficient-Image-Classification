# Modified ResNet for CIFAR-10 Classification

## Overview

Involves developing a customized version of the Residual Network (ResNet) architecture designed to optimize image classification accuracy on the CIFAR-10 dataset while maintaining a constraint of no more than 5 million trainable parameters. The goal is to create a model that combines efficiency in terms of size and computational demands with high performance, making it suitable for devices with limited storage capacity such as wearables and embedded systems. The project showcases an innovative approach to scaling down a powerful deep learning model without significantly compromising its accuracy.

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
