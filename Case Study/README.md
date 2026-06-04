# Sales Analysis

A Python-based exploratory data analysis project using 12 months of sales data to uncover business insights.

---

## Questions Explored

1. **What was the best month for sales? How much was earned that month?**
   - Monthly sales are aggregated and visualized to identify peak revenue periods.

2. **What city sold the most product?**
   - Sales are broken down by city to reveal top-performing markets across the US.

3. **What time should we display advertisements to maximize the likelihood of customers buying products?**
   - Order timestamps are analyzed by hour to find the optimal windows for ad targeting.

4. **What products are most often sold together?**
   - Co-purchase patterns are identified to uncover product bundling opportunities.

5. **What product sold the most? Why do you think it sold the most?**
   - Top-selling products are ranked by quantity ordered, with price as a potential explanatory factor.

---

## Dataset

- **Source:** Monthly CSV files stored in the `Sales_Data/` folder
- **Columns:** `Order ID`, `Product`, `Quantity Ordered`, `Price Each`, `Order Date`, `Purchase Address`
- **Coverage:** 12 months of US sales data across multiple cities

---

## Technologies Used

- Python 3
- Pandas
- Matplotlib

---

## How to Run

1. Clone this repository
2. Place your monthly CSV files inside a `Sales_Data/` folder
3. Open `SalesAnalysis.ipynb` in Jupyter Notebook
4. Run all cells from top to bottom
