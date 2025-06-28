# WQP-OB-TASK-5-
# 🍷 Wine Quality Prediction - Internship Task (Oasis Infobyte)

This project was developed as part of my internship at **Oasis Infobyte**, focused on predicting the quality of wine using machine learning techniques. The prediction is based on various physicochemical properties of wine such as acidity, alcohol, density, and more.

## 📁 Dataset

- Source: Provided during internship (CSV format)
- Features: 
  - `fixed acidity`, `volatile acidity`, `citric acid`, `residual sugar`, `chlorides`, 
  - `free sulfur dioxide`, `total sulfur dioxide`, `density`, `pH`, `sulphates`, `alcohol`
- Target: `quality` (integer rating of wine from 3 to 9)

---

## 📊 Project Objectives

- Clean and preprocess the wine dataset
- Explore data distribution and correlation between features
- Train multiple classification models
- Evaluate performance and compare results

---

## 🧰 Tools and Technologies

- **Python**
- **Pandas, NumPy** - Data manipulation
- **Matplotlib, Seaborn** - Data visualization
- **Scikit-learn** - Model building and evaluation
  - `RandomForestClassifier`
  - `SGDClassifier`
  - `SVC (Support Vector Classifier)`
- **Jupyter Notebook**

---

## ⚙️ ML Pipeline Steps

1. **Data Cleaning**: Handled nulls and dropped irrelevant columns (like `Id`)
2. **EDA**: Used heatmaps, pairplots, and distribution plots
3. **Feature Scaling**: Used `StandardScaler` to normalize input features
4. **Model Training**:
    - Random Forest
    - Stochastic Gradient Descent
    - Support Vector Machine
5. **Model Evaluation**: Accuracy score, classification report, confusion matrix

---

## 📌 Key Learnings

- Applied machine learning to a real-world chemical dataset
- Learned to interpret model outputs and choose suitable algorithms
- Practiced EDA, data preprocessing, and result communication

---


