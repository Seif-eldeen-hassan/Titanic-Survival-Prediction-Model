# 🚢 Titanic - Machine Learning from Disaster

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Learning-orange?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-white?style=for-the-badge&logo=pandas)

A comprehensive binary classification project to predict passenger survival on the Titanic. This notebook covers the entire Data Science pipeline: from raw data exploration to advanced feature engineering and model optimization.

## 🎯 Objective
The goal is to predict whether a passenger survived or not based on features like age, gender, social class, and family size.

## 🛠️ Tech Stack
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn
- **Model Used:** Random Forest Classifier (or your specific model)

## 🔍 Project Pipeline

### 1. Exploratory Data Analysis (EDA)
- Analyzed survival rates based on **Sex** (Female survival rate was significantly higher).
- Investigated the impact of **Pclass** on survival.
- Visualized age distribution and its correlation with survival.

### 2. Feature Engineering & Cleaning
- **Handling Missing Values:** Imputed missing values for `Age`, `Embarked`, and handled the `Cabin` column.
- **Feature Creation:** - Extracted **Titles** (Mr, Mrs, Miss, etc.) from names.
    - Created **FamilySize** by combining `SibSp` and `Parch`.
    - Developed an **IsAlone** feature.
- **Encoding:** Converted categorical variables into numerical format using One-Hot Encoding/Label Encoding.

### 3. Model & Evaluation
The project utilizes a **Random Forest Classifier**, tuned to handle the nonlinear relationships in the data.

**Results:**
- **Accuracy:** ~80-83% (Verify based on your last run).
- **Evaluation Metrics:** Confusion Matrix, Precision, and Recall.



[Image of Machine Learning Pipeline]


## 📈 Key Insights
- **Gender** was the strongest predictor of survival.
- Passengers in **First Class (Pclass 1)** had a much higher chance of survival.
- Smaller families had better survival rates compared to individuals traveling alone or with very large families.

---
## 👨‍💻 Author
**Seif Eldeen Hassan**
* AI & Data Science Student at FCAI, Cairo University.
* Founder & CEO of Baddel.
