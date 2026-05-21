# Retail Sales Insight & Trend Analysis

A Python-based data analysis project that explores retail sales data to understand customer purchasing behavior, revenue distribution across categories, and pricing trends. The project cleans unstructured text data, computes total financial metrics, and creates clear data visualizations using Matplotlib.

## Features & Data Workflow
* **Data Cleaning:** Handled missing values check and performed string stripping (`.str.strip()`) to remove whitespace from categories.
* **Feature Engineering:** Calculated a dynamic `Total_amount` column by multiplying product price and quantity.
* **Time-Series Preparation:** Converted the date fields into standard datetime format for chronological trend tracking.
* **Data Aggregation:** Grouped transactions by category to calculate total revenue distribution.

## Tech Stack Used
* **Language:** Python
* **Libraries:** Pandas, Matplotlib
* **Environment:** Jupyter Notebook / JupyterLab

## Key Insights & Visualizations

### 1. Total Revenue by Category (Bar Chart & Pie Chart)
* **Electronics** is the leading revenue generator, contributing over **62.2%** of total sales.
* **Clothing** accounts for **17.9%**, followed closely by **Home Decor** at **16.2%**.
* **Accessories** has the lowest share at **3.7%**.

### 2. Price vs Quantity (Scatter Plot)
* Analyzed the correlation between product pricing and transaction volumes.
* High-priced items generally see smaller order quantities, while lower-priced items attract bulk purchases.

### 3. Sales Trend Over Time (Line Chart)
* Monitored the fluctuation of daily prices and general sales momentum across different dates.

## How to Run This Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/retail-sales-analysis.git](https://github.com/your-username/retail-sales-analysis.git)
   cd retail-sales-analysis