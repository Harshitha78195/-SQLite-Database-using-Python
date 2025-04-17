# Sales Data Analysis with SQLite & Python

This project demonstrates how to analyze and visualize sales data stored in an SQLite database using Python, Pandas, and Matplotlib.

---

## What This Project Includes

### 1. **Database**
- SQLite database: `sales_data.db`
- Table: `sales`
- Fields: `id`, `product`, `quantity`, `price`

### 2. **Python Script Tasks**
- Connects to the SQLite database
- Runs SQL queries to:
  - Calculate total revenue by product
  - Find the top-selling product by quantity
  - Compute average price per product
  - Get overall quantity sold and total revenue
- Loads data into pandas DataFrames
- Prints summaries to the console
- Plots bar charts using matplotlib
- Saves visualizations as PNG images

---

## How to Run

1. Make sure `sales_data.db` is in the same directory.
2. Run the script with:
   ```bash
   python sales_analysis.py
