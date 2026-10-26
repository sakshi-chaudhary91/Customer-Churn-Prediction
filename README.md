# Customer Churn Prediction using TensorFlow & Keras

A deep learning project built to predict customer churn using an Artificial Neural Network (ANN). Developed and trained on Kaggle with Tesla T4 GPU acceleration, achieving **86.35% test accuracy**.

## 🚀 Project Overview
Customer churn is a critical metric for subscription-based businesses. This model analyzes customer demographic, behavioral, and account attributes to identify whether a customer is likely to stay or leave.

## 🧠 Model Architecture
The neural network is built using a sequential API in Keras:
* **Input Layer:** 11 features (`input_shape=(11,)`)
* **Hidden Layer 1:** Dense (32 neurons, `ReLU` activation)
* **Hidden Layer 2:** Dense (16 neurons, `ReLU` activation)
* **Output Layer:** Dense (1 neuron, `Sigmoid` activation for binary output)

## 📊 Performance & Results
* **Test Accuracy:** 86.35%
* **Optimization:** Adam Optimizer with binary crossentropy loss.
* **Regularization:** Early stopping implemented on validation loss (`patience=10`) to prevent overfitting.

## 🛠️ Tech Stack & Libraries
* **Python**
* **TensorFlow / Keras** (Deep Learning & GPU acceleration via XLA)
* **Scikit-Learn** (Data preprocessing & evaluation metrics)
* **Pandas & NumPy** (Data manipulation)
* **Matplotlib & Seaborn** (Data visualization & confusion matrix plotting)
