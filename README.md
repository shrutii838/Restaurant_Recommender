# 🍽️ Restaurant Recommendation System

## 📌 Overview
This is a **content-based restaurant recommendation system**.
It recommends restaurants to users based on their preferences like cuisine, price range, online delivery availability, and minimum rating.

The model uses **TF-IDF vectorization** and **cosine similarity** to match user preferences with restaurant features.

---

## 🛠️ Features
- **Interactive input** to choose:
  - Cuisine
  - Price range (1=Low, 4=High)
  - Online delivery (Yes/No)
  - Minimum rating
- Returns **Top N most similar restaurants**.
- Uses **content-based filtering** for recommendations.
- Built with **Python, Pandas, Scikit-learn**.

---

## 📂 Dataset
The dataset contains restaurant details such as:
- Cuisines
- Price range
- Aggregate rating
- Online delivery availability
- City & locality

> *(Dataset was provided as part of the internship tasks.)*

---

## 🚀 How to Run
### 1️⃣ Open in Google Colab
Click the badge below to run the notebook instantly in Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shrutii838/Restaurant_Recommender/blob/main/Restaurant_Reccomendation_system.ipynb)

---

### 2️⃣ Run Locally
```bash
# Clone the repository
git clone https://github.com/shrutii838/Restaurant_Recommender.git

# Navigate into the folder
cd Restaurant_Recommender

# Install dependencies
pip install pandas scikit-learn

# Run the script
python restaurant_recommender.py
