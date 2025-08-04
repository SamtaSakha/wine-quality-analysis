# 🍷 Wine Quality Analysis

This project focuses on predicting the quality of wine using machine learning techniques based on various physicochemical attributes such as acidity, alcohol content, and pH. The dataset contains observations for red and white wines, with a quality score ranging from 0 to 10 (based on sensory evaluation).

## 📌 Problem Statement
Wine quality ratings are subjective and expensive to obtain. The goal is to build a classifier that can automatically predict the quality of wine using measurable chemical properties, helping wine producers maintain consistent quality and reduce costs.

---

## 📂 Dataset Features

**Input Variables (Physicochemical Tests):**
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

**Target Variable:**
- `quality` (score between 0 and 10, later simplified into three categories: low, medium, high)

---

## 🛠️ Techniques Used

- Data Cleaning and Handling Missing Values
- Exploratory Data Analysis (EDA) & Visualizations
- Correlation Matrix and Feature Importance
- Quality Class Simplification
- Standardization (using `StandardScaler`)
- Machine Learning Model: **Random Forest Classifier**
- Model Evaluation: Confusion Matrix & Classification Report

---

## 📊 Results

- Simplified classification into **low**, **medium**, and **high** quality helped reduce class imbalance.
- **Alcohol**, **sulphates**, and **volatile acidity** were found to be the most important predictors of wine quality.
- Random Forest performed well without heavy hyperparameter tuning.

---

## 📈 Future Improvements

- Hyperparameter tuning (e.g. GridSearchCV)
- Try regression to predict exact quality score
- Use additional classifiers like SVM, XGBoost, or Voting Classifiers
- Feature selection or dimensionality reduction (e.g. PCA)

---

## 💾 Dataset Source

- UCI Machine Learning Repository  
- Combined and cleaned version in `.csv` format is included in this repo.

