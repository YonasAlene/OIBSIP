Retail Sales Data Analysis

Project Overview
This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using Python. The goal is to understand sales patterns, customer behavior, product category performance, and relationships between numerical variables.

Objectives
- Inspect and understand the dataset
- Check data types, missing values, and duplicates
- Calculate descriptive statistics
- Analyze monthly and quarterly sales trends
- Explore customer age groups and gender distribution
- Analyze product category sales and revenue
- Examine correlations between numerical variables
- Identify business insights and provide recommendations

Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

Dataset
The dataset contains 1,000 retail transactions and 9 columns:
- Transaction ID: Unique transaction identifier
- Date: Date of the transaction
- Customer ID: Unique customer identifier
- Gender: Customer gender
- Age: Customer age
- Product Category: Category of the purchased product
- Quantity: Number of units purchased
- Price per Unit: Price of one unit
- Total Amount: Total transaction value

Analysis Performed
1. Data Inspection
- Dataset shape
- Column names and data types
- Missing-value check
- Duplicate-value check

2. Descriptive Statistics
- Mean
- Median
- Mode
- Standard deviation

3. Sales Trend Analysis
- Monthly sales trends
- Quarterly sales trends

4. Customer Analysis
- Age-group distribution
- Gender distribution
- Average spending by age group

5. Product Category Analysis
- Sales quantity by product category
- Revenue by product category

6. Correlation Analysis
A correlation matrix and heatmap were used to examine relationships between Age, Quantity, Price per Unit, and Total Amount.

Key Findings
- Electronics generated the highest revenue.
- Beauty generated the lowest revenue.
- May 2023 recorded the highest monthly sales.
- January 2024 recorded the lowest monthly sales.
- Customers aged 46-55 represented the largest age group.
- The gender distribution was relatively balanced: 51% female and 49% male.
- Customers under 18 had the highest average transaction amount.
- Price per Unit had a strong positive correlation with Total Amount (approximately 0.85).

Business Recommendations
1. Maintain sufficient inventory and promotional support for the high-performing Electronics category.
2. Investigate pricing, product selection, customer demand, and marketing strategies to improve Beauty category performance.
3. Use monthly and quarterly sales patterns to improve inventory and promotional planning.
4. Consider both customer volume and average spending when targeting customer segments.
5. Monitor pricing strategies and their effect on transaction value.

Dataset Limitation
The dataset contains product categories but does not include individual product names or product IDs. Therefore, a true Top 10 Best-Selling Products analysis could not be performed at the individual-product level. Product performance was instead analyzed at the category level.

Project File
The main analysis is available in the Jupyter Notebook:
Retail_Sales_EDA.ipynb

How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries:
pip install pandas numpy matplotlib seaborn jupyter
3. Place the dataset CSV file in the project directory.
4. Open Jupyter Notebook.
5. Open Retail_Sales_EDA.ipynb.
6. Run the notebook cells from top to bottom.

Author
Yonas Alene

This project was created as a practical Data Analytics and Exploratory Data Analysis project.
