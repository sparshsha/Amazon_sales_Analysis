# Amazon_sales_Analysis

## Project Overview
This project presents an analysis of Amazon sales data using Python libraries, including Pandas, Matplotlib, Seaborn, and NumPy. The data comprises various sales-related attributes such as Order ID, Date, Status, Fulfilment, Sales Channel, ship-service-level, Category, Size, Courier Status, Qty, currency, Amount, ship-city, ship-state, ship-postal-code, ship-country, and B2B. This readme will guide you through the project and its key insights.

## Project Content
The project uses Jupyter Notebook to analyze a dataset containing 128,976 entries and 21 columns. It starts with data cleaning and exploration, then moves on to more specific analyses, using Pandas for data manipulation and Matplotlib and Seaborn for data visualization.

### Data Cleaning
- Dropped columns 'PendingS' and 'New' due to their lack of data.
- Removed rows with NaN values.
- Corrected data types for certain columns (like 'ship-postal-code' and 'Date') to ensure proper data analysis.
- After cleaning, the dataset contained 37,514 entries and 19 columns.

### Exploratory Data Analysis (EDA)
The exploratory analysis used various visualization techniques to identify trends and key insights:
- **Category Distribution**: A histogram showing the distribution of product categories.
- **Size Trends**: A count plot revealed that most customers preferred M-sized products.
- **Courier Status and Shipment**: A bar plot illustrating the relationship between Courier Status and Order Status.
- **Order Status Analysis**: Analyzed the status of orders to identify patterns.
- **B2B Customers**: A pie chart showing that 99.3% of customers were retailers while 0.8% were B2B buyers.
- **State-wise Analysis**: A count plot showing the distribution of orders across states, revealing Maharashtra as the state with the highest sales.

## Project Insights
Based on the analysis, the following insights were derived:
- **Popular Product Category**: T-shirts were the most popular product category.
- **Preferred Size**: M-sized products were the most preferred among buyers.
- **Fulfilment Method**: Most orders were fulfilled through Amazon's Easy Ship program.
- **Key Customer Base**: The business mainly served retailers and had a significant customer base in Maharashtra.
- **Courier Status**: A majority of orders were shipped successfully, with a small fraction cancelled or on the way.

## Conclusion
This project provides a detailed analysis of Amazon sales data, offering insights into customer preferences, fulfillment methods, and order distribution across various attributes. The analysis showcases Python's capabilities in data analysis and visualization, using popular libraries like Pandas, Matplotlib, and Seaborn.

## How to Run
To run this project, you need a Jupyter Notebook environment with Pandas, Matplotlib, Seaborn, and NumPy installed. Open the Jupyter Notebook and execute the code sections in sequence to reproduce the analysis and visualizations.

## License
This project is for educational purposes only and is not for commercial use. The data used in this project is anonymized and does not contain any personal information.
