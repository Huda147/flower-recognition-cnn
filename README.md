# 🌸 Flower Recognition using CNN

A deep learning project to classify different types of flowers using Convolutional Neural Networks (CNN) in TensorFlow/Keras.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Demo](#demo)
- [License](#license)

---

## 📖 Overview

This project focuses on image classification of flower species using a CNN-based model. The goal is to automatically recognize and categorize flower types from images using supervised learning.

---

## 🗂 Dataset

- The dataset should be placed in the `Datasets/Training_set` folder.
- Images are resized to **64x64 pixels** for training.
- Flower categories are inferred from the folder names.

> ⚠️ Ensure your dataset follows the structure: `Datasets/Training_set/<class_name>/<images>`

---

## 🧠 Model Architecture

The model is built and trained with:
- **Image Augmentation:** Rescale, shear, zoom, horizontal flip
- **Model Type:** Sequential CNN
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam
- **Metrics:** Accuracy

All training logic and architecture details are available in the Jupyter notebook.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flower-recognition-cnn.git
   cd flower-recognition-cnn
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook FlowerRecognition.ipynb
   ```

---

## 📊 Results

| Metric     | Value |
|------------|-------|
| Accuracy   | XX%   |
| Loss       | YY    |

_Update this table after training completion._

---

## 🔭 Future Improvements

- Add validation and testing metrics
- Use transfer learning (e.g., ResNet, MobileNet)
- Deploy as a web app with Gradio or Streamlit
- Visualize confusion matrix and misclassifications

---

## 🌐 Demo

Coming soon...

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).
