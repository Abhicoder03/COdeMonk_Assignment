# CodeMonk_Assignment
# 🧠 Fashion Product Multi-Label Classification with Deep Learning

## 📌 Overview

This project involves building a multi-label deep learning model to classify fashion product images into multiple categories including:

- **Color**
- **Product Type** (e.g., T-shirt, Shoes)
- **Season** (e.g., Summer, Winter)
- **Gender** (Men, Women, Unisex)

We leverage the **Fashion Product Images Dataset** available on Kaggle for training and testing.

---

## 🔗 Dataset

**Download from:** [Fashion Product Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)

This dataset includes images along with metadata like gender, article type, base color, and season.

---

## 🛠️ Tech Stack

- **Language:** Python 🐍
- **Frameworks:** PyTorch (preferred), TensorFlow/Keras (optional)
- **EDA & Visualization:** Pandas, Matplotlib, Seaborn
- **Image Handling:** OpenCV, PIL
- **Model Evaluation:** scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

A comprehensive EDA was performed to understand the distribution of:

- Gender, product type, base color, and season
- Class imbalance and missing values
- Image dimensions and format consistency

The insights from EDA helped in preprocessing decisions and model architecture.

---

## 🧠 Model Architecture

- Convolutional Neural Network (CNN) backbone (ResNet18/34 or custom CNN)
- Multi-head output layer for handling multiple targets
- Loss functions:
  - CrossEntropyLoss for categorical outputs
  - Weighted loss for class imbalance (if needed)
- Training with image augmentations (random crop, flip, normalization)

---

## 📈 Results

# 🧪 Amazon Test Cases

I tested our model on **real-world fashion images** taken from Amazon screenshots.

For this product model predicts![black_tshirt1](https://github.com/user-attachments/assets/738ff505-55c3-4faa-8b04-49e2bd543470)

![image](https://github.com/user-attachments/assets/48fd0897-1287-4924-bdca-63f66c2aa065)



*Note: Ensure screenshots are cropped to product areas for better results.*

---


