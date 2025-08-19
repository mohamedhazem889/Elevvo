# 🌲 Forest Cover Type Classification

This project applies machine learning models to predict **forest cover types** using cartographic and environmental data from the **covtype.csv** dataset.

---

## 🔍 Project Workflow

### 1. 📂 Data Preparation
- Loaded dataset (`covtype.csv`)
- Checked data types, distributions, and class balance
- Handled missing values and outliers

### 2. 📊 Exploratory Data Analysis (EDA)
- Visualized feature distributions and class imbalance
- Correlation checks and statistical summaries
- Plots with **Matplotlib** and **Seaborn**

### 3. 🛠 Preprocessing
- Scaled numerical features with **StandardScaler**
- Prepared data splits for training and testing

### 4. 🤖 Modeling
- **Logistic Regression** (baseline)
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**

### 5. 📈 Evaluation
- Confusion Matrix visualization
- Classification Report (Precision, Recall, F1-score)
- Cross-validation for model comparison

### 6. 🎯 Hyperparameter Tuning
- GridSearchCV & RandomizedSearchCV to optimize Random Forest & XGBoost
- Identified best-performing model configuration

### 7. 💾 Model Deployment
- Saved trained models using **Joblib**

---

## ⚙️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Missingno)
- **Scikit-learn** (Random Forest, Decision Tree, Logistic Regression, Evaluation, Tuning)
- **XGBoost**
- **Joblib** (Model persistence)

---

## 📊 Results
- Random Forest & XGBoost achieved strong performance in predicting forest cover types
- Confusion matrix highlighted class-specific performance
- Hyperparameter tuning improved accuracy and generalization

---
