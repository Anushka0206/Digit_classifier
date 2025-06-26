# 🧠 Handwritten Digit Recognition

This is a minimal Python project that trains a neural network to recognize handwritten digits from the **MNIST** dataset using **TensorFlow/Keras**.

The entire logic (data loading, model building, training, and prediction) is contained in `digit_classifier.py`.

---

## 📦 Features

- Loads the MNIST dataset (60,000 training + 10,000 test images)
- Trains a simple neural network with two hidden layers
- Evaluates accuracy on the test set
- Allows prediction on custom digit images (optional)

---

## 🖥️ Getting Started

### 1. Install Requirements
pip install tensorflow numpy matplotlib
### 2. Run the Classifier
python digit_classifier.py
## 🏗️ Model Structure
Input: 28 x 28 pixels (grayscale image)

Flatten: → 784 values

Dense: 128 units (ReLU)

Dense: 32 units (ReLU)

Output: 10 units (Softmax for digits 0–9)
