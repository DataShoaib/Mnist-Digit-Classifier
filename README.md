# 🔢 MNIST Digit Classifier (ANN)

![MNIST Sample](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## 📌 Overview
This project implements a handwritten digit classifier using an Artificial Neural Network (ANN).

Dataset: MNIST  
Task: Classify digits from 0 to 9  
Input: 28x28 grayscale images  
Output: Digit class (0–9)

Images → Normalize → Flatten → Dense Layers → Softmax Output

---

## 🧠 Why ANN?

- Used as a baseline deep learning model
- Helps understand:
  - Forward propagation
  - Backpropagation
  - Activation functions
- Simple and effective for small grayscale datasets like MNIST

---

## ⚙️ How It Works

1. Load MNIST dataset
2. Normalize pixel values (0–255 → 0–1)
3. Flatten 28x28 image into 784 vector
4. Pass through Dense layers
5. Final Softmax layer outputs probability for digits 0–9

---

## ❌ Limitation of ANN

- Flattens image → loses spatial structure
- Does not automatically detect edges or patterns
- CNN performs better for complex image tasks

---

## 🚀 Future Improvement

Upgrade to CNN for:
- Better feature extraction
- Higher accuracy
- Better generalization
