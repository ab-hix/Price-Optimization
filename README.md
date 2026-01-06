# 📈 Price Optimization using Demand Sensitivity (Python)

## 🔍 Overview
This project implements a **price optimization engine** that determines the optimal product price by modeling customer demand sensitivity and maximizing revenue using numerical optimization techniques.

Unlike traditional elasticity-based approaches, this project uses **demand-response modeling combined with optimization algorithms**, making it suitable for real-world pricing strategy analysis.

---

## 🎯 Objectives
- Model demand response to price changes
- Maximize revenue using numerical optimization
- Simulate pricing scenarios for business decision-making
- Visualize optimal pricing outcomes

---

## 🧠 Methodology
1. **Data Preparation**
   - Cleaned and filtered pricing and sales data
2. **Demand Modeling**
   - Linear demand approximation based on historical data
3. **Revenue Function**
   - Revenue = Price × Demand
4. **Optimization**
   - Used SciPy’s optimizer to identify revenue-maximizing price
5. **Scenario Analysis**
   - Simulated revenue across a range of prices
6. **Visualization**
   - Revenue curve with optimal price marker

---

## 📊 Dataset
**Retail Price Optimization Dataset (Kaggle)**  
🔗 https://www.kaggle.com/datasets/suddharshan/retail-price-optimization

The dataset contains historical pricing and sales information suitable for demand modeling and price optimization.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

---

## 📈 Results
- Identified optimal price that maximizes revenue
- Demonstrated demand sensitivity to pricing changes
- Built a reusable pricing simulation framework
