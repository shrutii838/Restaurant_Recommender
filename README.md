# 🍽️ Restaurant Analytics & Recommendation System

## 📌 Overview
This repository contains my **Cognifyz Machine Learning Internship** tasks, focusing on restaurant data analysis, recommendation, prediction, and classification.  
The goal is to demonstrate different machine learning techniques applied to real-world restaurant datasets.

---

## 📂 Tasks Included

### **🔹 Task 1 — Restaurant Rating Prediction**
Predicts the **Aggregate Rating** of a restaurant using features such as `Price range`, `Votes`, `Online delivery availability`, and `Cuisine type`.  
Model: **Linear Regression**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shrutii838/Restaurant_Recommender/blob/main/Rating_prediction.ipynb)

---

### **🔹 Task 2 — Restaurant Recommendation System**
A **content-based filtering** system that recommends restaurants based on **user preferences** like cuisine, price range, online delivery availability, and minimum rating.  
Model: **TF-IDF + Cosine Similarity**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shrutii838/Restaurant_Recommender/blob/main/Restaurant_Reccomendation_system.ipynb)

---

### **🔹 Task 3 — Cuisine Classification**
Classifies the **primary cuisine** of a restaurant based on price, rating, online delivery availability, and votes.  
Model: **Random Forest Classifier** (Interactive Prediction Tool)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shrutii838/Restaurant_Recommender/blob/main/Cuisine_classifier.ipynb)

---

## 📊 Dataset
The dataset contains restaurant details such as:
- Cuisines
- Price range
- Aggregate rating
- Online delivery availability
- Votes
- City & locality

**File in repo:** `restaurant_dataset.csv`

---

## 🚀 How to Run Locally
```bash
# Clone the repository
git clone https://github.com/shrutii838/Restaurant_Recommender.git

# Navigate into the folder
cd Restaurant_Recommender

# Install dependencies
pip install pandas scikit-learn

# Run any script locally
python filename.py

cd Restaurant_Recommender

# Install dependencies
pip install pandas scikit-learn

# Run the script
python restaurant_recommender.py
