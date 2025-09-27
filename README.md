# CIFAR-10 Image Classification using CNN in TensorFlow

This project implements a Convolutional Neural Network (CNN) to classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) into 10 categories:
**airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck.**

## 📌 Project Overview
- Dataset: CIFAR-10 (60,000 images of size 32×32)
- Framework: TensorFlow / Keras
- Model: Custom CNN with Conv2D, MaxPooling, Flatten, and Dense layers
- Training: 10 epochs with Adam optimizer
- Evaluation: Accuracy and loss visualization, test set performance

## 🚀 Features
- Train CNN on CIFAR-10 dataset
- Evaluate model accuracy and loss
- Predict on test samples
- Custom image prediction support (resized to 32×32)

## 📊 Results
- Achieved ~72% test accuracy after 10 epochs
- Accuracy improves with a deeper CNN architecture

## 🛠️ How to Run
```bash
# Clone this repository
git clone https://github.com/Zafir547/CIFAR-10-Image-Classification-using-CNN-in-TensorFlow.git

# Install dependencies
pip install tensorflow matplotlib
```

# Run the code cell step by step pipeline inside Jupyter notebook files: data preprocessing, training model, model evaluation, testing image predictions.
