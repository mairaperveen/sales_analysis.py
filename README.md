# Sales Data Analysis

## Overview

This project involves analyzing sales data for a fictional company called **TechGadgets**. The goal is to analyze sales data from the last month to understand customer preferences and improve marketing strategies.

### Objectives
- Store and organize sales data using lists, tuples, dictionaries, and sets.
- Perform data analysis to extract meaningful insights.
- Visualize the results using simple print statements.

## Data Description

The dataset used in this project consists of:
- **Sales Data**: A list of tuples, where each tuple contains:
  - `product_name`: Name of the product (e.g., Laptop)
  - `quantity_sold`: Number of units sold
  - `price_per_item`: Price per individual unit

### Example Data
```python
sales_data = [
    ("Laptop", 10, 800),
    ("Smartphone", 25, 600),
    ("Tablet", 15, 300),
    ("Smartwatch", 20, 200),
    ("Laptop", 5, 800), 
    ("Smartphone", 10, 600)
]
Solution Steps
Store Sales Data: Initialize the sales data as a list of tuples.
Initialize Structures: Create a set for unique products and a dictionary for total sales.
Process Data: Loop through the sales data to populate the set and dictionary.
Display Results:
Print the list of unique products.
Print a summary of total sales for each product.
Analyze:
Identify the product with the highest sales.
Visualization:
Visualize sales totals using a simple bar-like format in the console.
How to Run
Make sure you have Python installed (preferably version 3.x).
Save the provided Python script as sales_analysis.py.
Open a terminal or command prompt.
Navigate to the directory where the script is saved.
Run the script using the following command:
bash
Copy code
python sales_analysis.py
Example Output
markdown
Copy code
Unique Products Sold:
- Laptop
- Smartphone
- Tablet
- Smartwatch

Sales Summary:
Laptop: $12000
Smartphone: $21000
Tablet: $4500
Smartwatch: $4000

Product with the Highest Sales: Smartphone ($21000)

Basic Insights Visualization:
Laptop: ************
Smartphone: *********************
Tablet: *****
Smartwatch: ****
License
This project is for educational purposes and is not intended for commercial use.
