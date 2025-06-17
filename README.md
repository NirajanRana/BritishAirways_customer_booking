# 📊 Predictive Modeling of BritishAirways_Customer Bookings

This project focuses on building a predictive model to analyze customer booking behavior using machine learning techniques. It walks through data preprocessing, exploration, feature engineering, and model training using Python and key data science libraries.

---

## 📁 Dataset

- **File**: `customer_booking.csv`
- **Encoding**: `ISO-8859-1`
- **Content**: Customer booking-related information (exact features are explored within the notebook)

---

## 📌 Objectives

- Understand the dataset through exploratory data analysis (EDA)
- Perform data cleaning and transformation
- Engineer useful features for modeling
- Train a machine learning model to predict customer behavior

---

## 📦 Libraries Used

    ```python
    
    import pandas as pd
    import numpy as np
    from sklearn.model_selection import train_test_split
    from sklearn.ensemble import RandomForestClassifier
    from sklearn.metrics import classification_report, confusion_matrix
    import matplotlib.pyplot as plt
    import seaborn as sns

### 🔍 Workflow Overview
## 1. Exploratory Data Analysis (EDA)
Load dataset

Use .info(), .head(), and .describe() for structure and summary

Plot histograms, boxplots, and correlation heatmaps

## 2. Data Cleaning
Handle missing or inconsistent values

Remove irrelevant features

## 3. Feature Engineering
Create new features based on existing columns

Encode categorical variables for modeling

## 4. Model Building
Split data into training and testing sets

Train a Random Forest Classifier

Evaluate using:

Accuracy Score

Confusion Matrix

Classification Report

### 📈 Output
Visual data insights

Well-structured cleaned dataset

Predictive model with evaluation results

### 📈 Model Performance
### ✅ Model Used: Random Forest Classifier

## 🎯 Accuracy Achieved: 86%

Additional metrics such as precision, recall, and F1-score are available in the classification report.

### 🚀 Getting Started
To run this notebook:

Clone the repository or download the notebook and CSV file.

Make sure Python and required libraries are installed:

```bash

pip install pandas numpy scikit-learn matplotlib seaborn
Launch the Jupyter Notebook and run cells sequentially.
