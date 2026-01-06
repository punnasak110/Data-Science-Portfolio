# Price Optimization & Risk Analysis 📉💰

This project demonstrates how to determine the **Optimal Selling Price** using **Quantile Regression** to account for market uncertainty.

## 🚀 Key Concepts
1. **Beating the Average**: Unlike standard regression (OLS) that predicts *average* demand, **Quantile Regression** models the *entire distribution* of demand (e.g., Best-Case vs. Worst-Case scenarios).
2. **Risk-Aware Pricing**:
   - **Optimistic Strategy (90th Percentile)**: Pricing for high demand periods.
   - **Conservative Strategy (10th Percentile)**: Safety-net pricing to ensure volume during downturns.

## 🛠 Techniques Used
- **Synthetic Data**: Simulating realistic demand with price elasticity and heteroscedastic noise.
- **Statsmodels**: Implementing `QuantReg` for 10th, 50th, and 90th percentile modeling.
- **Scipy Optimize**: finding the revenue-maximizing price ($P^*$) for each risk profile.

## 📂 Files
- `Optimization_Price_Final.ipynb`: The main notebook containing the full analysis and optimization engine.
