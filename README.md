# 🍽️ Food Image Classifier & Calorie Estimator

A deep learning project that classifies food images into 101 categories using the Food-101 dataset and estimates their calorie content — helping users make informed dietary choices.

---

## 🔍 Features

- 🧠 **Image Classification** using MobileNetV2 (Transfer Learning)
- 📸 Upload any food image and get instant predictions
- 🔢 **Calorie estimation** based on predicted food class
- 📊 Trained on 95,000+ images from [Food-101](https://www.kaggle.com/datasets/hari31416/food-101)
- 🌐 Optional Gradio interface for easy use

---

## 📁 Dataset

- **Source:** [Food-101 by hari31416](https://www.kaggle.com/datasets/hari31416/food-101)
- **Size:** ~5 GB
- **Classes:** 101 food categories (e.g., pizza, samosa, sushi, cheesecake)
- **Structure:** Pre-divided into `train/` and `validation/` folders

---

## ⚙️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib (for image display)
- Gradio (optional UI)

---

## 🧪 How It Works

1. Load and preprocess image data (224x224)
2. Use MobileNetV2 for transfer learning
3. Train a classifier head with 101 outputs
4. Predict food class from uploaded image
5. Map predicted class to its average calorie value

---

## 🚀 How to Run

### On Google Colab

```bash
1. Mount Google Drive
2. Upload your Kaggle API key (kaggle.json)
3. Download & unzip the dataset
4. Run all cells in the notebook
