# mix-optimizer
# 📈 Product Mix Optimization using Linear Programming

This project solves a **business optimization problem** using **Linear Programming (LP)** and **PuLP** in Python. The scenario involves determining the optimal number of two products to manufacture in order to **maximize total profit** while respecting machine usage constraints.

---

## 🧠 Problem Statement

A company manufactures **two products** (Product A and Product B). Each product requires time on two machines and contributes differently to profit. The goal is to find the **optimal production quantity** of each product without exceeding the available time on the machines.

---

## 💡 Problem Formulation

### Objective:
> Maximize Profit:  
> **Z = 30x + 40y**  
Where:
- `x` = Units of Product A
- `y` = Units of Product B

### Subject to Constraints:
3x + 4y ≤ 240 (Machine 1 time constraint) 2x + 3y ≤ 180 (Machine 2 time constraint) x ≥ 0, y ≥ 0 (Non-negativity constraints)

---

## 🧪 Tools & Libraries

- Python
- [PuLP](https://coin-or.github.io/pulp/) – Linear Programming library

---

## 📁 Project Structure

product-mix-optimizer/ ├── optimization_model.ipynb # Jupyter Notebook with problem and solution ├── README.md # You're here └── requirements.txt # Project dependencies


---

## ⚙️ How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/product-mix-optimizer.git
cd product-mix-optimizer
2. Install Requirements
pip install -r requirements.txt
3. Run the Notebook
Open optimization_model.ipynb in Jupyter Notebook or VS Code and run the cells.

✅ Output Example
Status: Optimal
Optimal Units of Product A = 0.00
Optimal Units of Product B = 60.00
Maximum Profit = ₹2400.00

📊 Business Insights
To achieve maximum profit of ₹2400, the company should produce:

0 units of Product A

60 units of Product B

This solution ensures efficient use of machine time without exceeding the limits.

🙋 Author
Developed by Kartik Shripatre
As part of Internship Task 4: Optimization using Linear Programming.



