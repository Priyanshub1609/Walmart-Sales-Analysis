# Walmart Sales Analysis and Forecasting

## Project Overview

This project focuses on analyzing historical Walmart sales data to understand sales patterns, store performance, and the effect of external factors such as holidays and economic conditions. Along with data analysis, a time-series forecasting model is used to predict future weekly sales.

The main goal of the project is to gain business insights from the data and demonstrate practical data analysis and forecasting skills using Python.


## Dataset

The dataset contains weekly sales data from multiple Walmart stores along with additional information such as:

* Store ID
* Weekly sales
* Holiday flag
* Temperature
* Fuel price
* CPI
* Unemployment rate

---

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Prophet

---

## What Was Done in This Project

### 1. Data Cleaning and Preprocessing

* Checked for missing values and data types
* Converted date columns into proper datetime format
* Prepared the dataset for analysis and modeling

### 2. Exploratory Data Analysis (EDA)

* Analyzed sales distribution across stores
* Identified high-performing and low-performing stores
* Visualized trends, outliers, and patterns using graphs
* Studied the impact of holidays on weekly sales

### 3. Correlation and Regression Analysis

* Explored relationships between weekly sales and economic factors
* Built a linear regression model to understand how external variables influence sales

### 4. Time Series Forecasting

* Used Facebook Prophet to model weekly sales trends
* Captured seasonality and overall sales patterns
* Generated future sales forecasts

---

## Key Insights

* Some stores consistently generate higher weekly sales than others
* Holiday weeks show noticeable changes in sales behavior
* Economic indicators such as unemployment and CPI have a measurable impact on sales
* Time-series models help in understanding long-term trends and seasonality

---

## Project Structure

```
walmart-sales-analysis/
│── Capstone_project_Walmart.ipynb
│── Walmart.csv
│── README.md
```

---

## How to Run the Project

1. Clone the repository
2. Install required Python libraries
3. Open the Jupyter Notebook
4. Run the cells step by step

---

## Future Improvements

* Try advanced forecasting models like ARIMA or LSTM
* Perform feature engineering to improve prediction accuracy
* Build a dashboard to visualize sales insights interactively

---

## Author

**Priyanshu**
Data Analysis & Machine Learning Enthusiast


