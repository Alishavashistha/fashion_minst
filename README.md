# Fashion MNIST Classification

This repository implements a neural network from scratch using NumPy to classify images from the Fashion MNIST dataset

 📌 Features

- Pure NumPy implementation (no deep learning libraries)
- Manual implementation of forward and backward propagation
- Data augmentation (rotations and shifts)
- Supports mini-batch gradient descent
- Model saving based on best test accuracy


🧠 Network Architecture

- **Input Layer**: 784 (28x28 flattened grayscale image)
- **Hidden Layer**: 128 units with `sigmoid`
- **Output Layer**: 10 units with `softmax`

📁 Folder Structure
fashion_mnist_classification/
├── fashion_mnist_classification.ipynb
├── model1/
│ ├── W0.npy
│ ├── W1.npy
│ ├── B0.npy
│ ├── B1.npy

📊 Results
Peak Test Accuracy: ~88%
Epochs: 500+
Optimizer: Manual SGD with L2 regularization

