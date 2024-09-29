# Sales Analysis Dashboard

## Overview

The **Sales Analysis Dashboard** provides a comprehensive visualization of sales data over the past four years. This dashboard is designed to help users identify trends, analyze customer behavior, and optimize sales strategies.

## Features

- **Monthly Sales Trends**: Visualizes total sales over time to identify seasonal patterns.
- **Quantity by Price Groups**: Analyzes sales quantities categorized into Low, Mid, and High price ranges.
- **Top Products and Customers**: Highlights the best-selling products and the most engaged customers.
- **Category Analysis**: Evaluates which segments are driving sales growth.

## Data Source

The dashboard utilizes sales data with the following tables:

1. **Products**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Category of the product.
   - `Price`: Price of the product.
   - `Stock`: Quantity available in stock.

2. **Customers**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Email`: Email address of the customer.
   - `Phone`: Phone number of the customer.
   - `RegistrationDate`: Date the customer registered.

3. **Sales**
   - `SaleID`: Unique identifier for each sale.
   - `ProductID`: The product sold.
   - `CustomerID`: The customer who made the purchase.
   - `SaleDate`: Date of the sale.
   - `Quantity`: Quantity sold.
   - `TotalAmount`: Total amount for the sale.

## Getting Started

1. **Install Power BI**: Ensure you have Power BI Desktop installed on your computer.
2. **Open the File**: Download the `Sales_Analysis_Dashboard.pbix` file and open it with Power BI Desktop.
3. **Refresh Data**: If you need to update the data, refresh the dataset using the built-in Power BI functionalities.

## Usage

- Use the filters to customize your view by date and other criteria.
- Click on different visualizations to explore deeper insights.
- Clear filters using the "Clear Filters" button for a fresh view.

## Contribution

Contributions are welcome! Please feel free to submit a pull request or open an issue.
