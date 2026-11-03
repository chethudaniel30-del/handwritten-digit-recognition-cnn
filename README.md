# Handwritten Digit Recognition Using CNN

## Week 5 Project Report
**Virtual Data Science with Python Internship**

### Project Overview
This project implements a **Convolutional Neural Network (CNN)** using TensorFlow and Keras to recognize handwritten digits from 0 to 9 using the MNIST dataset.

The model learns image features through convolutional and pooling layers and classifies handwritten digit images into ten categories.

### Dataset
- Dataset: MNIST Handwritten Digits
- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28 pixels
- Number of classes: 10 (digits 0–9)
- Image format: Grayscale

### Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### CNN Architecture
The model consists of:
1. Input layer (28 × 28 × 1)
2. Convolutional layer (32 filters)
3. Max pooling layer
4. Convolutional layer (64 filters)
5. Max pooling layer
6. Flatten layer
7. Dense layer (128 neurons)
8. Dropout layer (0.3)
9. Output layer (10 classes, Softmax activation)

**Total trainable parameters:** 225,034

### Model Training
- Optimizer: Adam
- Loss function: Sparse Categorical Cross-Entropy
- Epochs: 5
- Batch size: 128
- Validation split: 10%

### Model Performance

| Metric | Result |
|---|---:|
| Training
