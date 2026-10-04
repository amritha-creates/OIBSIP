# EDA on Retail Sales Data

## Internship
Oasis Infobyte – Data Analytics Internship

## Task
Level 1 – Task 1: EDA on Retail Sales Data

## Objective
The objective of this project is to explore and analyze retail sales data using Python and identify useful patterns and business insights.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains 1,000 retail transaction records and 9 original columns, including:
- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Analysis Performed

### 1. Data Inspection
- Checked dataset shape and data types.
- Checked for missing values.
- Generated descriptive statistics.
- Calculated mean, median, mode, and standard deviation.

### 2. Sales Trend Analysis
- Analyzed monthly sales.
- Analyzed quarterly sales.
- Visualized sales trends using line charts.

### 3. Customer Demographic Analysis
- Created age groups.
- Analyzed age-group distribution.
- Compared age groups by gender.

### 4. Product Category Analysis
- Analyzed revenue by product category.
- Compared sales across Beauty, Clothing, and Electronics.

### 5. Correlation Analysis
- Created a numerical correlation matrix.
- Visualized relationships using a correlation heatmap.

### 6. Additional Analysis
- Analyzed total sales by gender.

### 7. Data Quality
- Checked for missing values.
- Checked for duplicate records.
- The dataset contained no missing values or duplicate rows.

## Key Findings

- Q4 2023 recorded the highest quarterly sales at ₹126,190.
- Electronics generated the highest category revenue at ₹156,905.
- The 46–55 age group had the highest number of transaction records.
- Female customers generated slightly higher total sales than male customers.
- Price per Unit and Total Amount had a strong positive correlation of 0.85.
- The dataset does not contain individual product names, so a Top 10 Products analysis could not be performed.

## Business Recommendations

1. Focus promotions and inventory planning on historically strong sales periods.
2. Strengthen the Electronics category through inventory planning and targeted promotions.
3. Develop marketing campaigns for different customer age groups and genders.
4. Monitor pricing and product mix because price per unit has a strong relationship with total transaction amount.

## Project Files

- `EDA_Retail_Sales.ipynb` – Main analysis notebook
- `retail_sales_dataset.csv` – Dataset
- `README.md` – Project documentation
