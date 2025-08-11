# 🧠 Introvert–Extrovert Personality Prediction

This project predicts whether a person is **Introverted** or **Extroverted** based on various social and behavioral features.  
It uses **Machine Learning** to classify personality types from structured data.

## 📂 Project Overview
The model analyzes multiple features such as:
- Time spent alone
- Stage fear
- Social event attendance
- Going outside frequency
- Drained after socializing
- Friends circle size
- Post frequency on social media

By cleaning anomalies and training classification algorithms, the model achieves accurate predictions for personality type.

## 📊 Dataset
- **Source:** [Kaggle Personality Dataset] 
- **Rows:** N samples  
- **Target Variable:** `Personality` → (`Introvert` or `Extrovert`)
- **Cleaning Steps:**
  - Removed duplicates
  - Handled missing values
  - Removed out-of-range values
  - Removed extreme outliers using the IQR method

## 🛠 Technologies Used
- Python 3.x
- Pandas, NumPy (data cleaning & analysis)
- Matplotlib, Seaborn (visualization)
- Scikit-learn (model training)
- Google Colab (development)
- GitHub (version control)

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/rojadasappa/ml_introvert-extrovert-prediction.git


