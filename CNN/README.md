# Convolutional Neural Network (CNN) for CIFAR-10

This repository contains a Jupyter Notebook that implements a Convolutional Neural Network (CNN) for image classification on the **CIFAR-10 dataset** using PyTorch. The notebook provides an end-to-end pipeline, from loading the dataset to training and evaluating the model.

---

## Features

- **Dataset**: CIFAR-10, a dataset of 60,000 32x32 color images in 10 classes.
- **Model Architecture**:
  - Two convolutional layers with ReLU activations.
  - Max-pooling for down-sampling.
  - Fully connected layers for classification.
  - Log Softmax activation for output probabilities.
- **Framework**: Built using PyTorch, leveraging TorchVision for dataset handling and utilities.
- **Device Compatibility**: Supports both CPU and GPU (if available).
- **Metrics**: Tracks training and validation loss to monitor performance.

---

## Dataset

The **CIFAR-10** dataset consists of:

- 50,000 training images.
- 10,000 testing images.
- 10 Classes: `plane`, `car`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`.

### Dataset Handling

The dataset is automatically downloaded using TorchVision with the following lines:

```python
trainset = torchvision.datasets.CIFAR10(root='./data', train=True, download=True, transform=transform)
testset = torchvision.datasets.CIFAR10(root='./data', train=False, download=True, transform=transform)
```
