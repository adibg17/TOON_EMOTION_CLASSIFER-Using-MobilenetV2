# 🎭 TOON Emotion Classifier using MobileNetV2

This project classifies emotions in cartoon characters (Tom and Jerry) using transfer learning with the MobileNetV2 architecture. The model performs **multi-output classification**—detecting both the **character** and their **emotion** from the given image.

---

## 📁 Project Structure

TOON_EMOTION_MobileNetV2/
├── Toon_Emotion_MobileNetV2.ipynb # Google Colab notebook
├── model/ # Trained model weights (optional)
└── dataset/ # Not included due to size

yaml
Copy
Edit

---

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

![Character and Emotion Report](dc899aab-0928-4c76-a1d0-5c5c2923d26d.png)

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

## ⚡ Future Improvements

- Improve emotion detection with more training data
- Balance class distribution
- Apply data augmentation and hyperparameter tuning
- Deploy model using Streamlit or Flask

---

## 👤 Author

Aditya BG  
Third-Year Computer Science Student  
📧 Contact: [LinkedIn / GitHub / Email if you wish to add]

---

## 🏷️ Tags

`mobilenetv2` `emotion-classification` `transfer-learning` `multi-output-model` `toon-emotion` `cnn`
