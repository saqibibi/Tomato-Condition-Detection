# 🍅 Tomato Condition & Disease Detection

## 📌 Description

This project uses Deep Learning (CNN) to analyze tomato images and classify them based on:

* Disease type (if present)
* Ripeness condition (Ripe, Unripe, Old)

The model is trained on image data and can predict the condition of a tomato from a given input image.

---

## 🧠 Features

* Image classification using Convolutional Neural Networks (CNN)
* Detects:

  * Tomato diseases
  * Tomato condition (Ripe / Unripe / Old)
* Data augmentation for better accuracy
* Model evaluation using:

  * Accuracy graphs
  * Confusion matrix
  * ROC curve

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Dataset

Download and extract dataset.zip before running the project.
The dataset is included inside the `dataset/` folder.
It contains categorized images of tomato leaves and tomatoes based on:

* Disease classes
* Ripeness stages

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. (If required) Mount Google Drive:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Ensure dataset path is correctly set
4. Run all cells sequentially

---

## 📊 Output

* Predicted class (Disease / Condition)
* Training & validation accuracy graphs
* Loss curves
* Confusion matrix visualization

---

## 🎯 Future Improvements

* Use Transfer Learning (ResNet / MobileNet)
* Deploy using Streamlit Web App
* Improve dataset size for higher accuracy

---

## 👨‍💻 Author

Saqib Khan
