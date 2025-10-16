# 🧠 Deep Learning-Based Melanoma Detection Using XceptionNet and DenseNet121

This project implements deep learning models for **automated melanoma detection** — a severe form of skin cancer. Using advanced CNN architectures (**XceptionNet** and **DenseNet121**) with **transfer learning**, the model classifies dermoscopic images as *melanoma* or *non-melanoma* with high accuracy.

---

## 🧩 Project Overview

* **Objective:** Early and accurate detection of melanoma using deep learning
* **Techniques Used:** Transfer Learning, Image Augmentation, Normalization
* **Frameworks:** TensorFlow, Keras, OpenCV, scikit-learn, Matplotlib
* **Dataset:** [HAM10000 Skin Lesion Dataset](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
* **Environment:** Jupyter Notebook (Python 3.x)

---

## 📊 Results Summary

| Model                    | Accuracy | Precision | Recall | F1-Score |
| ------------------------ | -------- | --------- | ------ | -------- |
| DenseNet121 (White Skin) | 98.5%    | 97.8%     | 98.2%  | 98.0%    |
| DenseNet121 (Dark Skin)  | 99.0%    | 98.9%     | 99.2%  | 99.0%    |

✅ The proposed model achieves **near-perfect accuracy** on both dark and light skin datasets, demonstrating its robustness and fairness.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rsumanth25/Melanoma-Detection.git
cd Melanoma-Detection
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

```bash
jupyter notebook train_model.ipynb
```

### 4️⃣ Predict a New Image

```bash
python predict.py --image path/to/image.jpg
```

---

## 🧠 Features

* Automated melanoma classification
* Works across **light and dark skin tones**
* Generates **Confusion Matrix & ROC Curves**
* Easy-to-use `predict()` function for new images
* High performance with **DenseNet121** fine-tuned on HAM10000

---

## 🧭 System Requirements

**Hardware:**

* Processor: Intel i3 or higher
* RAM: 4 GB minimum

**Software:**

* OS: Windows 10 / Linux
* Python 3.8+
* Jupyter Notebook

---

## 🚀 Future Enhancements

* Integration with **Flask/Streamlit** for real-time web deployment
* Add **Grad-CAM** visualizations for explainable AI
* Expand dataset with clinical metadata for improved accuracy

---

## 👨‍💻 Team Members

| Name                 | Roll Number |
| -------------------- | ----------- |
| **R. Sumanth Reddy** | 22R01A6255  |
| **A. Joshi**         | 22R01A6201  |
| **A. Dheeraj Rao**   | 22R01A6204  |
| **M. Raviteja**      | 22R01A6248  |
| **R. MadhuSai**      | 22R01A6256  |

---

## 🧑‍🏫 Guide

**Mr. A. Srinish Reddy**
Assistant Professor, Dept. of Computer Science and Engineering
CMR Institute of Technology, Hyderabad

---

## 🏛️ Institution

**CMR Institute of Technology (Autonomous)**
Affiliated to JNTUH, Approved by AICTE
Accredited by NAAC (A+) and NBA
📍 Kandlakoya (V), Medchal Dist., Hyderabad

---

## 🌟 Acknowledgment

We sincerely thank our guide, faculty, and department for their support and guidance throughout this project.

---

*Developed by Team Melanoma Detection – CMRIT (2024–25)*
