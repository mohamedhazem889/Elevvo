# 🏦 Loan Approval Prediction (Binary Classification)

This project builds a machine learning model to **predict loan approvals** from applicant data, addressing challenges like **missing values** and **imbalanced classes**.

---

## 🔍 Project Workflow  

### 1. 📂 Data Preparation  
- Loaded and cleaned dataset (`loan_approval_dataset.csv`)  
- Dropped unnecessary identifiers (Loan_ID)  
- Handled missing values using imputers  

### 2. 📊 Exploratory Data Analysis (EDA)  
- Examined class distribution → target variable was **imbalanced**  
- Visualized numerical & categorical features with **Matplotlib** and **Seaborn**  
- Checked missing patterns using **Missingno**  

### 3. 🛠 Preprocessing  
- Encoded categorical variables (Ordinal, One-Hot, Label Encoding)  
- Applied transformations for feature scaling  

### 4. 🤖 Model Building  
- Implemented multiple classifiers:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - SVM  
  - KNN  
  - Naive Bayes  

### 5. ⚖️ Handling Imbalanced Data  
- Baseline models (no balancing)  
- Class weights adjustment  
- Oversampling with **SMOTE**  

### 6. 📈 Evaluation  
- Primary metric: **F1-Score**  
- Additional metrics: Precision, Recall  

### 7. 🔍 Results  
- **Random Forest** (with class weights / SMOTE) delivered best performance  
- **Decision Tree with SMOTE** also achieved competitive results  
- Highlighted how balancing techniques improved minority class prediction  

---

## ⚙️ Tech Stack  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Missingno)  
- **Scikit-learn** (Logistic Regression, Decision Tree, Random Forest, SVM, KNN, Naive Bayes, Encoders, Metrics)  
- **Imbalanced-learn** (SMOTE)  

---

## 📊 Insights  
- Class imbalance significantly affected baseline results  
- Proper handling of imbalance (SMOTE / class weights) improved fairness across classes  
- Random Forest proved to be the most robust model for loan approval prediction  
