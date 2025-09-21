# Black-Litterman Portfolio Optimization

This project demonstrates a **portfolio optimization framework** using the **Black-Litterman model**, a quantitative finance approach that combines historical market data with subjective investor views to create more stable and diversified portfolios. 

The implementation is done entirely in **Python** using a Jupyter Notebook, focusing on practical applications of portfolio theory and optimization.

---

## 📌 Overview
Traditional mean-variance optimization (Markowitz model) often results in extreme and unstable portfolio weights due to estimation errors in expected returns.  

The **Black-Litterman model**, developed by Fischer Black and Robert Litterman at Goldman Sachs, addresses these challenges by:
- Combining **market equilibrium returns** with **investor views**.
- Producing more **diversified and intuitive asset allocations**.
- Reducing sensitivity to noisy data and assumptions.

This notebook demonstrates:
1. Data collection and preparation.
2. Calculation of implied equilibrium returns.
3. Integration of investor views into the model.
4. Portfolio optimization using the combined return estimates.
5. Visualization of portfolio performance and allocations.

---

## 🎯 Features
- Step-by-step implementation of the Black-Litterman model.
- Historical data analysis and visualization.
- Customizable investor views to reflect personal or institutional beliefs.
- Portfolio optimization with Python.
- Visual plots for portfolio weights and efficient frontiers.

---

## 🛠 Tech Stack
- **Python**  
- **Key Libraries:**
  - `pandas` - Data manipulation
  - `numpy` - Numerical analysis
  - `matplotlib` - Visualization
  - `cvxopt` - Portfolio optimization
  - `scipy` - Statistical computations

---

## 🚀 Getting Started

### 1. Clone the Repository
### 2. Install Required Packages

Install the necessary Python libraries:

pip install pandas numpy matplotlib cvxopt scipy

### 3. Open the Notebook

Then open Dhruv_Black_Litterman_PortfolioOptimization.ipynb and run the cells.

## 📊 Black-Litterman Workflow - 

Collect Historical Data – Load price data for selected assets.

Compute Equilibrium Returns – Derive implied returns using market cap weights and risk aversion.

Define Investor Views – Input subjective views about asset performance.

Blend Returns – Combine equilibrium returns with investor views using the Black-Litterman formula.

Optimize Portfolio – Calculate optimal asset weights using convex optimization.

Visualize Results – Display portfolio allocations and efficient frontier.


## References

Fischer Black & Robert Litterman, Global Portfolio Optimization, 1992.
Original Goldman Sachs Research Paper

## 5. 👤 Author

Dhruv Gohil
