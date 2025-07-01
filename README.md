# 🤖 Machine Learning Project

This repository presents a comprehensive machine learning project composed of three main parts:
1. Data Visualization (California Housing Prices)
2. Regression Modeling (California Housing Prices)
3. Classification (Online Shoppers Purchasing Intention)

Each part highlights the application of key machine learning concepts and techniques on real-world datasets.

---

## 📘 Table of Contents

- [1. Data Visualization](#1-data-visualization)
- [2. Regression](#2-regression)
- [3. Classification](#3-classification)

---

## 1. 📊 Data Visualization

### 📁 Dataset
- **File:** `housingdata.csv`  
- **Source:** StatLib Repository (California 1990 Census)
- **Features:**  
  - `longitude`, `latitude`, `housing_median_age`, `total_rooms`, `total_bedrooms`,  
  - `population`, `households`, `median_income`, `median_house_value`, `ocean_proximity`

### 🎯 Objective
- Explore the dataset to identify:
  - Feature distributions
  - Outliers
  - Correlations and trends
- Generate a **scatterplot matrix** to visualize relationships among features.

---

## 2. 📈 Regression

### 📁 Dataset
- Same dataset used from Part 1: `housingdata.csv`

### 🎯 Objectives

- Split dataset using the **Hold-Out method** (train/test split)
- Apply **forward feature selection** to construct regression models
- For each model:
  - Report **R² score**
  - Report **Mean Squared Error (MSE)**
- Identify and interpret the **best performing regression model**

### 🧠 Techniques Used

- Linear Regression
- Feature selection strategy: Forward selection
- Model evaluation: R² and MSE

---

## 3. 🧠 Classification

### 📁 Dataset
- **File:** `Online Shoppers Purchasing Intention Dataset`
- **Samples:** 12,330 user sessions
- **Features:** 17 input features + 1 target label (`Revenue`)
- **Target:** `Revenue` (binary classification: `True` for purchase, `False` for no purchase)

### 🔍 Feature Types
- Page visit statistics (`Administrative`, `Informational`, `Product Related`)
- Engagement metrics (`Bounce Rate`, `Exit Rate`, `Page Value`)
- Temporal data (`Month`, `Weekend`, `Special Day`)
- Technical context (`Browser`, `Operating System`, `Region`, `Traffic Type`)
- User type (`VisitorType`)

### 🎯 Objectives

- Apply **different classification algorithms**:
  - `Decision Tree`
  - `Naive Bayes`
  - `Lazy Classifier` (e.g., KNN)
  - `SVM`
  - `Ensemble Classifier` (e.g., Random Forest)
  
- Evaluate using two validation strategies:
  - **10-fold Cross-Validation**
  - **Hold-Out Method**
  
- For each experiment:
  - Report the **confusion matrix**
  - Compare results between validation strategies

### ⚙️ Preprocessing Techniques

- Label encoding for categorical variables
- Normalization of numerical features
- Handling missing values (if any)

### 📈 Performance Evaluation

- Compare models based on accuracy, precision, recall, and F1-score
- Justify the **best classifier** chosen by the group based on results

