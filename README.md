# Predictive Analytics Using Historical Data

## Project Overview

This project focuses on building a predictive model using historical sales data to forecast future trends. A Linear Regression model was developed to analyze sales patterns and predict future sales.

---

## Objective

- Build a predictive model to forecast sales trends.
- Clean and preprocess historical datasets.
- Perform feature engineering.
- Evaluate model performance.
- Visualize actual and predicted values.
- Generate business insights.

---

## Dataset

- **Dataset:** Sample Superstore Sales
- **Records:** 8,399
- **Features:** 23 columns

### Key Variables

- Order Date
- Sales
- Profit
- Discount
- Order Quantity
- Unit Price
- Shipping Cost

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Project Workflow

### Data Cleaning
- Checked for missing values.
- Removed duplicate records.

### Feature Engineering
Extracted:
- Year
- Month
- Day

from the Order Date column.

### Model Building
Implemented a **Linear Regression** model to predict sales.

### Model Evaluation
Performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Model Performance

| Metric | Value |
|----------|--------:|
| MAE | 713.86 |
| RMSE | 1376.18 |
| R² Score | 0.8567 |

The model explains approximately **85.67%** of the variance in sales, indicating good predictive performance.

---

## Visualizations

- Actual vs Predicted Sales
- Scatter Plot of Actual and Predicted Values

---

## Business Insights

- Sales are influenced by order quantity, unit price, discount, and profit.
- Historical data can be used to forecast future trends.
- Predictive analytics supports data-driven decision-making.

## Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
openpyxl
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Key Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Linear Regression
- Model Evaluation
- Predictive Analytics
- Data Visualization

---

## Conclusion

A Linear Regression model was developed using historical sales data to forecast future sales trends. The model achieved an **R² score of 85.67%**, demonstrating strong predictive capability and the effectiveness of machine learning techniques in supporting business decision-making.

---

## Author

**R Venkata Ramana**

GitHub: *Add your GitHub profile link*

LinkedIn: *Add your LinkedIn profile link*
