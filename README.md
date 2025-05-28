# Digit Classification CNN - Model Deployment Submission

This project performs image classification on handwritten digits (0–9) using a Convolutional Neural Network (CNN) and exports the trained model into three formats:

- TensorFlow SavedModel
- TensorFlow Lite (TFLite)
- TensorFlow.js (TFJS)

---

## 🧠 Model Overview

- **Architecture:** CNN with `Conv2D`, `MaxPooling2D`, `Dropout`, `Dense`
- **Framework:** TensorFlow / Keras
- **Input Shape:** 128x128 RGB images
- **Output:** One of 10 classes (digits 0 through 9)

---

## 🚀 Model Deployment Formats

| Format         | Use Case                          |
|----------------|-----------------------------------|
| SavedModel     | Inference on server-side or TensorFlow pipelines |
| TFLite         | Lightweight deployment on mobile or embedded devices |
| TFJS           | Run model in browser with JavaScript |

---

## 📝 How to Run

1. Open `notebook.ipynb`
2. Train the model using the provided dataset
3. Evaluate the model on training and testing sets
4. Export the model into `.tflite`, `.pb`, and `.json` formats
5. Use `label.txt` to map prediction indices to class labels

---

## 📦 Requirements

Make sure to install all required packages using:

```bash
pip install -r requirements.txt
```

---

## 🔖 Dataset

- Dataset Source: [Kaggle - Digits Updated](https://www.kaggle.com/datasets/karnikakapoor/digits)
- Structure: Each digit is placed in a folder named with its corresponding label (`0`–`9`)

---

## 👤 Author

Tatang Warianta  
Computer Science  
Universitas Negeri Semarang  