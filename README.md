# 🎭 TOON Emotion Classifier using MobileNetV2

This project classifies emotions in cartoon characters (Tom and Jerry) using transfer learning with the MobileNetV2 architecture. The model performs **multi-output classification**—detecting both the **character** and their **emotion** from the given image.


## 🧠 Model Overview

- **Base Model**: MobileNetV2 pretrained on ImageNet
- **Tasks**:
  - Character Classification: Tom or Jerry
  - Emotion Classification: Angry, Happy, Sad, Surprised
- **Framework**: TensorFlow & Keras (Google Colab)

---

## 📊 Results

### ✅ Character Classification
- **Accuracy**: 100%
- **Precision, Recall, F1**: 1.00 for both Tom and Jerry

### 😄 Emotion Classification
- **Accuracy**: ~58%
- **F1-Scores**:
  - Angry: 0.59
  - Happy: 0.56
  - Sad: 0.56
  - Surprised: 0.61

> 📷 *Refer to the visual classification report below:*

![Character and Emotion Report](Classification_Report.png)

---

## 🚀 Try It Yourself

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/Toon_Emotion_MobileNetV2.ipynb)

---

## 📷 Sample Data Structure

dataset/
├── Tom/
│ ├── Angry/
│ ├── Happy/
│ ├── Sad/
│ └── Surprised/
└── Jerry/
├── Angry/
├── Happy/
├── Sad/
└── Surprised/



---

## 🔧 Tools & Libraries

- Python
- MobileNetv2
- TensorFlow
- Google Colab
- Matplotlib, NumPy, Seaborn

---
## 🖼️ Sample Predictions

### 🔹 Tom – Predicted Emotion

![Tom Prediction](Tom_Predicted.png)

---

### 🔹 Jerry – Predicted Emotion

![Jerry Prediction](Jerry_Predicted.png)


## ⚡ Future Improvements

- Improve emotion detection with more training data
- Balance class distribution
- Apply data augmentation and hyperparameter tuning
- Deploy model using Streamlit or Flask

---

## 👤 Author

Aditya BG  
Third-Year Computer Science Student  
📧 Contact:adityabg11@gmail.com

---

## 🏷️ Tags

`mobilenetv2` `emotion-classification` `transfer-learning` `multi-output-model` `toon-emotion` `cnn`
