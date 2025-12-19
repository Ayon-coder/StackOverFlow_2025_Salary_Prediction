# Stack Overflow Salary Prediction

## 📌 Project Overview
This project focuses on predicting developers’ yearly compensation using data from the Stack Overflow Developer Survey.  
The objective is to build a baseline machine learning model that estimates salary based on professional experience, education level, developer role, country, and programming background.

---

## 🎯 Objective
- Predict `ConvertedCompYearly` using developer-related features
- Demonstrate a complete ML workflow: preprocessing → modeling → evaluation

---

## 📊 Dataset
- **Source:** Stack Overflow Developer Survey (public dataset)
- **Note:**  
  The dataset is not included in this repository due to its large size.  
  It can be downloaded from the official Stack Overflow website.

---

## 🧩 Features Used
- `WorkExp` – Years of professional experience  
- `YearsCode` – Years of coding experience  
- `EdLevel` – Highest education level  
- `DevType` – Developer role(s)  
- `Country` – Country of residence  
- `LanguageHaveWorkedWith` – Programming languages  
- `ConvertedCompYearly` – Target variable (salary)

---

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## 🔍 Data Preprocessing
- Removed missing and invalid salary values  
- Extracted primary programming language  
- Selected most frequent categories to reduce sparsity  
- Applied one-hot encoding for categorical features  

---

## 🤖 Machine Learning Model
- **Algorithm:** Linear Regression  
- **Train/Test Split:** 80% / 20%  
- **Target Variable:** `ConvertedCompYearly`

### Evaluation Metrics
- Mean Absolute Error (MAE)
- R² Score

---

## 📈 Model Evaluation
Model performance was evaluated numerically and visually using an Actual vs Predicted Salary comparison.  
The model captures general salary trends but struggles with extreme outliers due to the highly skewed nature of compensation data.

---

## ⚠️ Limitations
- Salary data is self-reported  
- Large salary outliers affect prediction accuracy  
- Linear regression does not handle skewed targets optimally  

---

## 🚀 Future Improvements
- Apply log transformation to salary values  
- Experiment with regularized models (Ridge, Lasso)  
- Include additional relevant features  
- Build an interactive salary prediction interface  

---

## 📌 Conclusion
This project demonstrates a practical application of machine learning on real-world survey data, highlighting both the strengths and limitations of linear regression for salary prediction tasks.

---
