# 🧹 Data Cleaning & Feature Engineering – Heart Disease Dataset  

## 📌 Project Overview  
This project applies **data cleaning** and **feature engineering** techniques on the **UCI Heart Disease dataset**.  
The objective is to transform raw, incomplete, and inconsistent medical data into a **structured dataset** ready for machine learning models.  

---

## 🎯 Objectives  
- Handle missing values, duplicates, and outliers  
- Perform feature encoding & scaling  
- Engineer new meaningful features  
- Apply **PCA** for dimensionality reduction  
- Prepare final dataset for ML training/testing  

---

## 🛠 Steps Performed  

### 🔹 Data Cleaning  
- Handled missing values (median for numeric, mode for categorical)  
- Removed duplicates  
- Fixed inconsistent formats (string casing, datatypes)  
- Converted object columns to numeric/datetime where applicable  
- Handled outliers using **IQR method**  

### 🔹 Feature Engineering  
- Created **Age Groups** (Young, Adult, Mid-age, Senior, Elder)  
- Added **Cholesterol-to-Age Ratio**  
- Encoded categorical variables:  
  - **Label Encoding** (binary categories)  
  - **One-Hot Encoding** (multi-class categories)  
- Normalized features using **StandardScaler**  
- Applied **PCA** (5 components) for dimensionality reduction  

### 🔹 Dataset Splitting  
- Train/Test Split (80/20) with stratification  
- Final cleaned dataset stored in CSV format  

---

## 📂 Repository Structure  
📂 Heart-Disease-Cleaning-Engineering
┣ 📄 heart_disease_uci.csv # Raw dataset
┣ 📄 heart_disease_cleaned.csv # Final cleaned dataset
┣ 📄 notebook.ipynb # Jupyter Notebook with all steps
┣ 📄 requirements.txt # Dependencies
┣ 📄 README.md # Project Documentation

yaml
Copy
Edit

---

## 📊 Visualizations  
- Missing values heatmap  
- Age distribution plot  
- Correlation heatmap  

---

## ⚙️ Tech Stack  
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn (LabelEncoder, StandardScaler, PCA, Train/Test Split)**  

---

## 🚀 Outcome  
The raw dataset was successfully cleaned and transformed into an **ML-ready format**.  
The processed dataset is suitable for building predictive models to detect **heart disease**.  

---

## 📌 Next Steps  
- Train machine learning models on the cleaned dataset  
- Compare performance of algorithms (Logistic Regression, Random Forest, XGBoost, etc.)  
- Visualize **feature importance** for medical insights  

---

## 🙌 Acknowledgments  
- Dataset: **UCI Machine Learning Repository – Heart Disease Dataset** 
