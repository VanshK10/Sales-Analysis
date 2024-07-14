# Sales-Analysis
## Online Retail Analysis

This project is an analysis of sales of an online store to check the most popular products by their recency, frequency and total expenditure. Then the products are predicted to be one of the best products using data science techniques.

## Project Structure

### **DATA**: Contains the raw dataset, modified dataset, and RFM table.
 -  `Online Retail.xlsx`: Raw dataset
 -  `Modified_Online_Retail.csv`: Modified dataset after cleaning and feature engineering
 -  `RFM_Table.csv`: RFM table with calculated metrics.
### **CODE**: Contains Jupyter notebooks for data cleaning, feature engineering, RFM analysis, and ML modeling.
  - `Online Sales.ipynb`: Data cleaning and feature engineering steps, RFM analysis and customer segmentation, machine learning model training and evaluation.
### **VISUALISATION**: Contains the Tableau workbook for visualizations.
  - `TableauWorkbook.twbx`: Tableau workbook with visualizations

## Getting Started

-First the raw data was cleaned using pandas library of python. Then the frequency by which each product is bought is calculated, and the total amount spent on each item too. Finally the recency of product purchase is calculated to create a RFM dataframe.
-Using the RFM criteria the products are given a score in each category from 1 to 4.
-This score is used to calculate the total RFM score. If it is above 9 then the product is having good and frequent sales. This can help in inventory managenment and to predict when to purchase fresh stock.
-Later these three parameters are fed to a decision tree classifier to train it to predict good products.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Tableau (for visualizations)


