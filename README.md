# FUTURE_ML_01
# 🛒 Walmart Weekly Sales Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Pandas-green)
![Visualization](https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-red)

## 📌 Project Overview

Retail companies rely heavily on data to understand customer demand and forecast sales.
This project focuses on analyzing Walmart sales data and building a **machine learning model to predict weekly sales** using historical data and economic indicators.

The project demonstrates a **complete data science workflow**, including:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Machine learning model training
* Model evaluation
* Data visualization

---

## 📊 Dataset Description

The dataset contains historical Walmart store sales data.

| Feature      | Description                                           |
| ------------ | ----------------------------------------------------- |
| Store        | Store identification number                           |
| Date         | Week of sales                                         |
| Weekly_Sales | Total weekly sales revenue                            |
| Holiday_Flag | Whether the week includes a holiday (1 = Yes, 0 = No) |
| Temperature  | Temperature of the week                               |
| Fuel_Price   | Regional fuel price                                   |
| CPI          | Consumer Price Index                                  |
| Unemployment | Unemployment rate                                     |

Target Variable:

**Weekly_Sales**

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab
* GitHub

---

## 🔎 Project Workflow

### 1️⃣ Data Loading

The dataset is imported and inspected using **Pandas** to understand structure and data types.

### 2️⃣ Data Preprocessing

* Converted date column into datetime format
* Extracted **year, month, and week features**
* Checked for missing values

### 3️⃣ Exploratory Data Analysis

EDA helps identify patterns and relationships in the data.

Visualizations included:

* Sales distribution
* Weekly sales trends
* Holiday vs non-holiday sales comparison
* Feature correlation heatmap

### 4️⃣ Machine Learning Models

Two regression models were implemented:

* **Linear Regression**
* **Random Forest Regressor**

The dataset was split into **training and testing sets (80/20)**.

### 5️⃣ Model Evaluation

Model performance was evaluated using:

* Mean Squared Error (MSE)
* R² Score
* Actual vs Predicted visualization
* Residual analysis

### 6️⃣ Feature Importance Analysis

The Random Forest model was used to identify which variables have the most impact on weekly sales predictions.

---

## 📈 Key Insights

* Holiday weeks generally experience **higher sales activity**.
* Economic indicators like **CPI and unemployment rate influence purchasing behavior**.
* Random Forest produced **more accurate predictions** compared to Linear Regression.

---

## 📊 Visualizations

The project includes several data visualizations:

* 📉 Sales Distribution Histogram
* 🔥 Correlation Heatmap
* 🎄 Holiday vs Non-Holiday Sales Comparison
* 📅 Weekly Sales Trend
* 📍 Actual vs Predicted Sales Plot
* 📊 Residual Error Plot
* ⭐ Feature Importance Graph

These visualizations help understand patterns in the data and evaluate model performance.

---

## 📂 Project Structure

```
walmart-sales-prediction/
│
├── Walmart.csv
├── Walmart_Sales_Prediction.ipynb
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone this repository

```
git clone https://github.com/yourusername/walmart-sales-prediction.git
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```
Walmart_Sales_Prediction.ipynb
```

4. Run all cells to reproduce the analysis and model training.

---

## 🎯 Project Outcome

The project successfully demonstrates how machine learning techniques can be applied to **predict retail sales and analyze economic factors affecting business performance**.

This type of analysis can help companies improve:

* demand forecasting
* inventory management
* pricing strategies

---

## 👨‍💻 Author

**Aryan Saini**
B.Tech Computer Science Engineering

Machine Learning | Data Analysis | Python
