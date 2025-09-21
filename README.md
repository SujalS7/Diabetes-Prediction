# 🩺 Diabetes Prediction using Machine Learning

This project focuses on building and comparing different **machine learning models** to predict the onset of diabetes based on diagnostic measurements.  
The dataset used is the **Pima Indians Diabetes Database**.

---

## 📊 Project Overview
The goal is to analyze patient health records and develop predictive models that can classify whether a patient is likely to develop diabetes.  
This project demonstrates the **end-to-end ML workflow** — from **data preprocessing** to **model evaluation** and **comparison**.

---

## 🛠️ Tech Stack
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Models:** Decision Tree, Support Vector Machine (SVM), Random Forest  

---

## 📂 Project Steps

### 🔹 1. Data Loading & Exploration
- Loaded the dataset and performed **EDA** (Exploratory Data Analysis).  
- Identified missing values (zeros in certain features).  

### 🔹 2. Data Preprocessing
- Replaced invalid zero values with median imputation.  
- Scaled features using **StandardScaler** for better model performance.  
- Split data into **80% training** and **20% testing** sets.  

### 🔹 3. Model Training
Trained and compared three classifiers:
- 🌳 **Decision Tree Classifier**  
- 📈 **Support Vector Machine (SVM)**  
- 🌲 **Random Forest Classifier**  

### 🔹 4. Model Evaluation
Evaluated models using:
- Accuracy ✅  
- Precision 🎯  
- Recall 📌  
- F1-score ⚖️  
- **ROC AUC Score**  
- Visualized **Confusion Matrices**  
- Plotted **ROC Curves**  

### 🔹 5. Model Comparison
- Random Forest outperformed other models overall.  
- Compared metrics side-by-side for final insights.  

---

## 📉 Results & Insights
- **Random Forest** achieved the best balance between accuracy and recall.  
- ROC AUC analysis showed strong discriminative ability.  
- Useful for **early diabetes detection support** in healthcare.  

