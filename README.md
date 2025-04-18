# 📊 TASK 7: Basic Sales Summary from SQLite using Python

## 🎯 Objective
Use SQL inside Python to pull simple sales information from a tiny SQLite database and display the results using print statements and a bar chart.

---

## 📂 Deliverables

✅ A Python script (`.py`) or Jupyter Notebook (`.ipynb`) that:

- Connects to a local SQLite database file `sales_data.db`
- Runs one or two SQL queries to:
  - Get total quantity sold per product
  - Get total revenue per product
- Displays the results using `print()`
- Visualizes revenue data using `matplotlib` (simple bar chart)
- Saves the chart as `sales_chart.png`

---

## 🛠️ Tools Used

- Python 3.x
- SQLite (via Python’s built-in `sqlite3`)
- `pandas`
- `matplotlib`
- Jupyter Notebook or any Python IDE (like VS Code)

---

## 📦 Dataset

A simple SQLite database named `sales_data.db` with one table:

**Table Name:** `sales`

| Column Name   | Data Type |
|---------------|-----------|
| id            | INTEGER   |
| product       | TEXT      |
| quantity      | INTEGER   |
| unit_price    | REAL      |
| date          | TEXT      |

> ✅ You can create this from a CSV file using a Python script.

---

## 🧪 How to Run

1. Make sure you have all files:
   - `sales_data.csv`
   - `create_db.py` (converts CSV to SQLite)
   - `sales_analysis.py` or `.ipynb`
   - `sales_data.db` (generated)
   - `sales_chart.png` (output)

2. Install Python packages (if not installed):
```bash
pip install pandas matplotlib
