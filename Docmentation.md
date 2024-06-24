# Sales Data Analysis

This repository contains a sample dataset of sales records and a Jupyter Notebook for data analysis using Pandas, Matplotlib, and Seaborn.

## Task 2: Data Analysis with Pandas

### Objective

Analyze a dataset using the Pandas library in Python.

### Description

- Use the Pandas library to load a dataset (e.g., CSV, Excel) containing sample data (e.g., sales records, student grades).
- Perform data exploration tasks such as filtering, sorting, and grouping data.
- Calculate summary statistics (mean, median, standard deviation) for numeric variables.
- Visualize data distribution and relationships using Matplotlib or Seaborn.

## Dataset

The dataset (`Sample.csv`) includes the following columns:

- `Date`: The date of the sale
- `Region`: The region where the sale was made (North, South, East, West)
- `Product`: The product sold (Widget A, Widget B, Widget C)
- `Quantity`: The quantity of the product sold
- `Price`: The price of the product

### Sample Data

| Date       | Region | Product  | Quantity | Price |
|------------|--------|----------|----------|-------|
| 2024-01-01 | North  | Widget A | 10       | 20.5  |
| 2024-01-02 | South  | Widget B | 15       | 30.0  |
| 2024-01-03 | East   | Widget A | 7        | 20.5  |
| 2024-01-04 | West   | Widget C | 20       | 25.0  |
| 2024-01-05 | North  | Widget B | 5        | 30.0  |
| 2024-01-06 | South  | Widget A | 12       | 20.5  |
| 2024-01-07 | East   | Widget C | 25       | 25.0  |
| 2024-01-08 | West   | Widget B | 30       | 30.0  |
| 2024-01-09 | North  | Widget C | 8        | 25.0  |
| 2024-01-10 | South  | Widget A | 14       | 20.5  |

## Analysis

The analysis notebook (`Analysis.ipynb`) performs the following tasks:

1. **Load the dataset**: Reads the CSV file into a Pandas DataFrame.
2. **Data Exploration**:
   - Filters data for a specific region.
   - Sorts data by quantity in descending order.
   - Groups data by product and calculates the total quantity sold for each product.
3. **Summary Statistics**:
   - Calculates mean, median, and standard deviation for the quantity sold.
4. **Data Visualization**:
   - Plots the distribution of quantities sold using a histogram.
   - Plots the relationship between quantity and price using a scatter plot.

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/FujoshiShidsuki/Data-Analysis-with-Pandas.git
