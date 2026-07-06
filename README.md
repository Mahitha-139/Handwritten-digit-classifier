# Handwritten Digit Classifier using MNIST

A beginner-friendly Artificial Intelligence and Machine Learning (AI/ML) project that builds a Deep Neural Network (DNN) to classify handwritten digits (0–9). This project uses the industry-standard **MNIST dataset** and **TensorFlow/Keras**.

## 🚀 Project Overview
This repository serves as a foundational "Hello World" project for Computer Vision. It takes images of handwritten numbers, processes them, and trains a machine learning model to predict the correct digit with high accuracy.

### Key Concepts Covered:
* **Data Normalization:** Scaling pixel values for faster model training.
* **Fully Connected Layers:** Building input, hidden, and output neural layers.
* **Activation Functions:** Utilizing `ReLU` for hidden layers and `Softmax` for multi-class probability outputs.
* **Model Evaluation:** Testing performance on unseen data to check for overfitting.

---

## 📊 Dataset
The project uses the **MNIST (Modified National Institute of Standards and Technology)** dataset, which is built into TensorFlow. 
* **Training Images:** 60,000 grayscale images of digits 0–9.
* **Testing Images:** 10,000 grayscale images.
* **Image Size:** 28x28 pixels.

---

## 🛠️ Requirements & Installation

Make sure you have Python installed. Clone this repository and install the required dependencies using pip:

```bash
# Clone the repository
git clone https://github.com

# Navigate into the project directory
cd handwritten-digit-classifier

# Install dependencies
pip install tensorflow numpy matplotlib
```

---

## 💻 How to Run

Execute the main Python script to train and test the model:

```bash
python digit_classifier.py
```

---

## 🏗️ Neural Network Architecture

The model is built using a sequential architecture with the following layers:

1. **Flatten Layer:** Converts the 2D image matrix ($28 \times 28$) into a 1D vector of 784 pixels.
2. **Dense Hidden Layer 1:** 128 neurons with `ReLU` activation.
3. **Dense Hidden Layer 2:** 64 neurons with `ReLU` activation.
4. **Dense Output Layer:** 10 neurons (one for each digit) with `Softmax` activation.

---

## 📈 Sample Results
After training for 5 epochs, the model typically achieves:
* **Training Accuracy:** ~98%
* **Test Accuracy:** ~97%

The script concludes by displaying a test image alongside the model's prediction using `matplotlib`.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to swap out the simple DNN for a Convolutional Neural Network (CNN) or add custom drawing predictions.
