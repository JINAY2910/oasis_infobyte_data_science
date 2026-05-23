# 🌟 Data Science & Machine Learning Projects

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains various machine learning and data science projects. The tasks cover diverse domains of machine learning including classification, regression, exploratory data analysis (EDA), and automated data downloading.

---

## 📂 Tasks & Notebooks Overview

### 1. 🚗 Car Price Prediction
* **Notebook:** [car_price_prediction.ipynb](./car_price_prediction.ipynb)
* **Goal:** Analyze used car data and build a predictive regression model to estimate car resale prices based on key vehicle features.
* **Techniques & Models:** 
  - Dynamic dataset download via `kagglehub` integration.
  - Comprehensive EDA & correlation heatmaps.
  - Categorical data encoding using `LabelEncoder`.
  - Trained a robust **Random Forest Regressor** to handle non-linear features.
* **Metrics Evaluated:** R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE).

---

### 2. 🪻 Iris Flower Classification
* **Notebook:** [iris_flower_classification.ipynb](./iris_flower_classification.ipynb)
* **Goal:** Classify species of iris flowers (Setosa, Versicolor, Virginica) based on sepal and petal dimensions.
* **Techniques & Models:**
  - Automated dynamic dataset downloading from a secure online CSV source.
  - Multi-class scatter plotting and pairplot visualizations.
  - Implemented **K-Nearest Neighbors (KNN)** classification algorithm.
* **Metrics Evaluated:** Accuracy Score, Confusion Matrix, and Classification Report (Precision, Recall, F1-Score).

---

### 3. 📈 Sales Prediction
* **Notebook:** [sales_prediction.ipynb](./sales_prediction.ipynb)
* **Goal:** Analyze advertising budget allocations (TV, Radio, Newspaper) and predict total sales revenue.
* **Techniques & Models:**
  - Linear relationships modeling and multi-channel visualization.
  - Multi-variable **Linear Regression** model for predictive mapping.
* **Metrics Evaluated:** R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE).

---

## 🛠️ Tech Stack
* **Language:** Python
* **Data Wrangling:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn`
* **Data Fetching:** `kagglehub`, `urllib` / `pandas` web-readers

---

## 🚀 How to Setup & Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/JINAY2910/oasis_infobyte_data_science.git
cd oasis_infobyte_data_science
```

### 2. Setup Virtual Environment (Recommended)
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook
```bash
jupyter notebook
```
Open any of the task notebooks inside the Jupyter environment and run the cells sequentially to reproduce the analysis and model evaluations.

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---
*Developed by Jinay Shah*
