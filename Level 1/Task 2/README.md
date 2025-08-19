# 🛍️ Mall Customers Segmentation

This project applies clustering techniques to segment customers based on their **annual income** and **spending score** using the **Mall_Customers.csv** dataset.

---

## 🔍 Project Workflow

### 1. 📂 Data Preparation
- Loaded and cleaned dataset (`Mall_Customers.csv`)
- Removed unnecessary columns (CustomerID)
- Renamed features for consistency

### 2. 📊 Exploratory Data Analysis (EDA)
- Descriptive statistics and distributions
- Visualizations with **Matplotlib** and **Seaborn**
- Checked missing values using **Missingno**

### 3. 🛠 Preprocessing
- Standardized numerical features with **StandardScaler**

### 4. 🤖 Clustering
- **K-Means Clustering**: applied to segment customers  
- **DBSCAN**: experimented for density-based clustering  

### 5. 📈 Evaluation
- Used **Silhouette Score** to evaluate clustering quality
- Compared performance of different algorithms

### 6. 🔍 Insights
- Segmented customers into meaningful groups
- Analyzed **average spending per cluster** to identify high-value segments

---

## ⚙️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Missingno)
- **Scikit-learn** (KMeans, DBSCAN, StandardScaler, Silhouette Score)

---

## 📊 Results
- K-Means provided clear customer segments based on income & spending score
- DBSCAN highlighted density-based group patterns
- Cluster-level spending analysis revealed distinct shopping behaviors

---
