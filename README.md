# E-commerce-project_EDA

## Project Overview

This project analyzes transaction data from a UK-based non-store online retail company that primarily sells all-occasion gifts. The dataset spans one year, from December 1, 2010, to December 9, 2011, and primarily includes wholesalers as customers.

## Data Details

- Company: UK-based non-store online retail
- Products: All-occasion gifts
- Customers: Mainly wholesalers (local and international)
- Transaction Period: December 1, 2010 - December 9, 2011

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Preparation

The analysis involves the following steps:

1. Loading Data:
   - Data is imported from a CSV file using Pandas.

2. Exploratory Data Analysis (EDA):
   - Basic statistics and visualizations are generated, including:
     - Boxplots and histograms for numeric variables (UnitPrice, Quantity, CustomerID)
     - Correlation heatmaps
     - Unique value counts and handling duplicates
     - Missing value treatment using the mean for symmetric distributions

3. Data Cleaning:
   - Duplicate rows are removed.
   - Negative values in the Quantity column are filtered out.
   - New columns are created for time-based analysis (Year_month, Month, Day, Hour).

## Analysis Steps

1. Orders Analysis:
   - Number of orders made by each customer.
   - Top 5 customers based on the number of orders.
   - Money spent by customers and top 5 customers based on spending.

2. Temporal Analysis:
   - Monthly, daily, and hourly distribution of orders.
   - Number of orders per country, excluding the UK.

3. Visualization:
   - Various plots (bar plots, line plots) to illustrate trends and patterns in customer behavior and sales.

## Usage

To run the analysis, ensure you have the necessary libraries installed. You can use the following command:

```bash
pip install pandas numpy matplotlib seaborn
```

Load the data by updating the file path in the script to point to your CSV file:

```python
df = pd.read_csv("path_to_your_data/data.csv", encoding='latin-1')
```

Run the script in a Python environment (e.g., Jupyter Notebook, Spyder) to generate visualizations and analyses.

## Conclusion

This project aims to provide insights into customer behavior and sales trends for the online retail company, aiding in decision-making and strategy formulation for future sales and marketing initiatives.

For any questions or further assistance, please contact thakuranjali1202@gmail.com.

Feel free to modify any sections as needed!
