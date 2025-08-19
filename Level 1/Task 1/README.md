# 📘 Student Exam Score Prediction

This project focuses on building and comparing regression models to estimate student exam scores using the **StudentPerformanceFactors.csv** dataset.  
The dataset includes features such as study hours, academic factors, and lifestyle habits.

---

## 🔍 Project Workflow

### 1. 📂 Data Preparation
- Loaded and explored the dataset (`StudentPerformanceFactors.csv`)
- Handled missing values and outliers
- Cleaned and structured data for modeling

### 2. 📊 Exploratory Data Analysis (EDA)
- Descriptive statistics and distribution checks  
- Correlation analysis  
- Visualizations with **Matplotlib**, **Seaborn**, and **Missingno**

### 3. 🛠 Preprocessing
- Imputation for missing values  
- Feature encoding (One-Hot & Ordinal Encoding)  
- Scaling and transformations (PowerTransformer)  
- Pipelines for reproducible preprocessing  

### 4. 🤖 Modeling
- **Linear Regression** (baseline model)  
- **Polynomial Regression** (feature expansion with `PolynomialFeatures`)  
- **Regularization Methods**: Ridge, Lasso, ElasticNet  
- **SGD Regressor** (gradient descent-based optimization)  

### 5. 📈 Evaluation
- Metrics: Root Mean Squared Error (RMSE) & R² Score  
- Compared models to identify the best-performing approach  

### 6. 💾 Model Deployment
- Exported trained models using **Joblib** for reuse/deployment

---

## ⚙️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Missingno)
- **Scikit-learn** (Linear Models, Preprocessing, Pipelines, Evaluation)
- **Joblib** (Model persistence)

---

## 📌 Key Highlights
- End-to-end regression pipeline  
- Experimentation with polynomial & regularized regression  
- Model comparison with multiple evaluation metrics  
- Deployment-ready models  

---

## 📊 Results
- Linear Regression provided a solid baseline  
- Polynomial and Regularized models improved predictive performance  
- Best model selected based on **RMSE** and **R²**

---
