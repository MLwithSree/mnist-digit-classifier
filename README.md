# 🧠 MNIST Digit Classifier using CNN

This is a Convolutional Neural Network built using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

- Dataset: [MNIST Digits](http://yann.lecun.com/exdb/mnist/) (also available via `keras.datasets`)

## 🧰 Tools Used

- Python
- TensorFlow / Keras
- Matplotlib / Seaborn

## 🚀 Model Architecture

- Conv2D (32 filters) → ReLU
- MaxPooling2D
- Conv2D (64 filters) → ReLU
- MaxPooling2D
- Flatten → Dense(64) → Dropout → Dense(10)

## 🎯 Accuracy Achieved

- Train Accuracy: 97%
- Test Accuracy: 95%


## 🔍 How to Run

```bash
pip install -r requirements.txt
