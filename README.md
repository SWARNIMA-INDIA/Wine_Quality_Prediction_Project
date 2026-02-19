# 🍷 Wine Quality Prediction (Machine Learning Project)

An end-to-end Machine Learning project that predicts wine quality using physicochemical properties.  
This project demonstrates data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## 📌 Project Objective
The goal of this project is to build a predictive model that can determine wine quality based on its chemical characteristics such as acidity, sugar, pH, alcohol content, etc.

---

## 📊 Dataset Information
- Dataset: Wine Quality Dataset  
- Contains Red & White wine samples  
- Target Variable: Quality score  

### 🔑 Features
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Type (Red/White)
- Quality (Target)

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Imported dataset using Pandas
- Checked shape, columns, and data types

### 2️⃣ Data Cleaning
- Handled missing values using imputation
- Converted categorical wine type into numerical form

### 3️⃣ Exploratory Data Analysis (EDA)
- Distribution plots & histograms
- Correlation heatmap
- Feature impact on wine quality

### 4️⃣ Feature Engineering
- Label encoding for wine type
- Feature scaling using MinMaxScaler

### 5️⃣ Model Building
- Train-test split
- Applied classification models (as implemented in notebook)

### 6️⃣ Model Evaluation
- Accuracy score
- Performance comparison
- Insights from predictions

---

## 📈 Key Insights
✔ Alcohol and sulphates positively influence quality  
✔ Volatile acidity negatively affects quality  
✔ Feature scaling improved model performance  
✔ Data imbalance observed in quality distribution  

---

## 🛠️ Tech Stack
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run the Project

```bash
git clone https://github.com/SWARNIMA-INDIA/wine-quality-prediction.git
cd wine-quality-prediction
pip install -r requirements.txt
jupyter notebook
