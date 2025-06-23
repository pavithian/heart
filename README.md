# Task 1 – Heart Disease Dataset Preprocessing

This repository contains the solution for **Task 1** of my AI & ML Internship.  
The objective was to clean and preprocess a real-world dataset to prepare it for machine learning tasks.

---

## 📌 Dataset Used

**Heart Disease UCI Dataset**  
Source: [Kaggle - Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

---

## 🎯 Objective

To perform data cleaning and preprocessing including:
- Handling missing values
- Encoding categorical features
- Normalizing/standardizing numerical columns
- Visualizing and removing outliers

---

## 📁 Files in This Repo

| File Name                          | Description                                      |
|-----------------------------------|--------------------------------------------------|
| `heart.csv`                       | Original dataset downloaded from Kaggle          |
| `task1_heart_preprocessing.ipynb` | Jupyter Notebook containing full preprocessing code |
| `README.md`                       | This readme file explaining the project          |

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ✅ Preprocessing Steps Performed

1. **Imported and explored the dataset**
   - Checked datatypes, null values, and basic stats.
2. **Handled missing values**
   - Simulated some missing data and filled using median.
3. **Encoded categorical variables**
   - Used one-hot encoding with `pd.get_dummies()`.
4. **Normalized numerical features**
   - Used `StandardScaler` from `sklearn`.
5. **Detected and removed outliers**
   - Used boxplot visualization and IQR method.

---

## 📊 Outcome

The dataset is now cleaned and ready for:
- Training machine learning models (classification)
- Further exploratory data analysis (EDA)
- Feature selection and modeling tasks

---

## 📬 Contact

*This task was completed as part of the AI & ML Internship Project.*


