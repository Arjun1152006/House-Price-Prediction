# 🏠 House Price Prediction

## 📌 Project Overview

This project was developed as part of a Data Science Internship (Week 1 Assignment). The objective is to build a machine learning model that predicts house prices based on various property features such as area, number of bedrooms, bathrooms, stories, parking spaces, and other housing characteristics.

The project includes data preprocessing, exploratory data analysis (EDA), visualization, model training, evaluation, and business insights.

---

## 🎯 Problem Statement

Real estate buyers and sellers often rely on estimates and outdated comparisons to determine property values. This project aims to create a predictive model that can estimate house prices accurately using historical housing data and machine learning techniques.

---

## 📂 Dataset

**Dataset:** Housing Prices Dataset

Source: Kaggle

https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

Dataset File:

* Housing.csv

---

## 🛠 Technologies Used

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📋 Project Tasks

### Task 1: Data Loading & Exploration

* Loaded dataset using Pandas
* Displayed first 10 records
* Checked dataset dimensions
* Identified target and feature columns
* Analyzed missing values

### Task 2: Data Cleaning

* Handled missing values
* Removed duplicate records
* Encoded categorical features
* Prepared data for machine learning

### Task 3: Model Building

* Train-Test Split (80%-20%)
* Linear Regression Model
* Random Forest Regressor Model
* Performance Evaluation using:

  * MAE (Mean Absolute Error)
  * RMSE (Root Mean Squared Error)
  * R² Score

### Task 4: Data Visualization

Generated the following visualizations:

1. House Price Distribution Histogram
2. Correlation Heatmap
3. Actual vs Predicted House Price Scatter Plot

### Task 5: Insights & Summary

* Identified most influential features
* Compared model performances
* Generated business recommendations

---

## 📊 Model Evaluation Metrics

The following metrics were used to evaluate model performance:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The Random Forest Regressor achieved better predictive performance compared to the Linear Regression model due to its ability to capture non-linear relationships in housing data.

---

## 📈 Key Insights

* Area is one of the strongest predictors of house price.
* Properties with more bathrooms and bedrooms generally have higher prices.
* Furnishing status and preferred location significantly impact property value.
* Random Forest performed better than Linear Regression on this dataset.
* Data visualization helped identify important feature relationships.

---

## 📁 Project Structure

HousePricePrediction/

├── analysis.ipynb

├── Housing.csv

├── summary.pdf

├── charts/

│ ├── price_distribution.png

│ ├── correlation_heatmap.png

│ └── actual_vs_predicted.png

└── README.md

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/HousePricePrediction.git
cd HousePricePrediction
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
analysis.ipynb
```

and run all cells.

---

## 📌 Future Improvements

* Hyperparameter tuning
* Feature engineering
* XGBoost and Gradient Boosting models
* Deployment using Flask/Streamlit
* Real-time house price prediction web application

---

## 👨‍💻 Author

Arjun Peddi

B.Tech – Artificial Intelligence & Machine Learning

Seshadri Rao Gudlavalleru Engineering College

Internship Project – Week 1

---
