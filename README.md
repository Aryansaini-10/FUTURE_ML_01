# FUTURE_ML_01
Walmart Weekly Sales Prediction (Machine Learning Project)
📌 Project Overview

This project analyzes Walmart sales data and builds a machine learning model to predict weekly sales based on economic and environmental factors. The goal is to explore patterns in retail sales and develop predictive models using data science techniques.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualization.

📊 Dataset Information

The dataset contains historical sales data for Walmart stores along with economic indicators.

Dataset Features:

Feature	Description
Store	Store ID number
Date	Week of recorded sales
Weekly_Sales	Total weekly sales of the store
Holiday_Flag	Indicates if the week includes a holiday (1 = Holiday, 0 = No Holiday)
Temperature	Temperature during that week
Fuel_Price	Fuel price in the region
CPI	Consumer Price Index
Unemployment	Unemployment rate

The target variable for prediction is Weekly_Sales.

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

🔍 Project Workflow
1. Data Loading

The dataset was imported and inspected using Pandas to understand its structure.

2. Data Preprocessing

Converted date column into datetime format

Extracted Year, Month, and Week features

Checked for missing values

3. Exploratory Data Analysis (EDA)

Several visualizations were used to explore relationships in the dataset:

Sales distribution

Holiday vs Non-holiday sales

Correlation heatmap

Weekly sales trend analysis

4. Model Training

Two machine learning models were implemented:

Linear Regression

Random Forest Regressor

The dataset was split into training and testing sets using an 80/20 ratio.

5. Model Evaluation

Model performance was evaluated using:

Mean Squared Error (MSE)

R² Score

Actual vs Predicted Sales visualization

Residual analysis

6. Feature Importance

Random Forest was used to determine which variables most influence weekly sales predictions.

📈 Key Insights

Holiday weeks generally show higher sales compared to regular weeks.

Economic indicators such as CPI and unemployment rate influence retail sales.

Random Forest provided better prediction performance compared to Linear Regression.

📊 Visualizations Included

The project includes several important visualizations:

Sales distribution histogram

Correlation heatmap

Holiday vs Non-Holiday sales comparison

Weekly sales trend

Actual vs Predicted sales graph

Residual plot

Feature importance chart

🚀 Conclusion

This project demonstrates how machine learning can be applied to predict retail sales using historical and economic data. The analysis highlights how external factors such as economic indicators and seasonal trends influence sales performance.

Such predictive models can help businesses make data-driven decisions in inventory planning, pricing, and demand forecasting.
👨‍💻 Author

Aryan Saini
B.Tech CSE Student
