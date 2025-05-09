# DA_623_Assignment
# CIFAR-10 Image Classification with CNN (TensorFlow/Keras)

This project demonstrates how to build and train a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html). The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes, with 6,000 images per class.

## 📌 Project Overview

- **Dataset**: CIFAR-10
- **Model Architecture**:
  - Convolutional layers with ReLU activation
  - Max Pooling layers
  - Fully connected (Dense) layers
  - Softmax output layer
- **Training**: 10 epochs with a batch size of 64
- **Validation Split**: 10% of training data
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Evaluation Metric**: Accuracy

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- TensorFlow 2.x
- NumPy

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/cifar10-cnn-tensorflow.git
   cd cifar10-cnn-tensorflow
   
## 🧠 Model Architecture
```text
Input: (32x32x3)
↓
Conv2D (32 filters, 3x3) + ReLU
↓
MaxPooling2D (2x2)
↓
Conv2D (64 filters, 3x3) + ReLU
↓
MaxPooling2D (2x2)
↓
Flatten
↓
Dense (512 units) + ReLU
↓
Dense (10 units) + Softmax




