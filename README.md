# Brain-Tumor-Detection-using-CNN


## 📌 Overview

A **Convolutional Neural Network (CNN)**–based project to classify **brain MRI images** into four categories: **glioma, meningioma, pituitary tumor, and no tumor**. The model is trained on grayscale MRI scans and achieves strong classification accuracy.

---

## 🧠 Dataset

MRI images organized into training and testing folders:

```
Brain_Tumor/
├── Training/ (glioma, meningioma, pituitary, notumor)
├── Testing/  (glioma, meningioma, pituitary, notumor)
```

Images are resized to **150 × 150** and converted to grayscale.

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* scikit-image
* Google Colab

---

## 🏗️ Model Architecture

```
Conv2D → MaxPooling → Flatten → Dense → Softmax
```

* Optimizer: Adam
* Loss: Sparse Categorical Crossentropy
* Epochs: 20
* Batch Size: 16

---

## 📊 Results

* Achieved **~94% accuracy** on the test dataset
* Successfully predicts tumor class for unseen MRI images

---

## 📌 Applications

* Medical image classification
* AI-assisted diagnosis systems
* Computer vision in healthcare

