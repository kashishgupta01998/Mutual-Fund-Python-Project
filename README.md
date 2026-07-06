# Creating a Mutual Fund Plan with Python

## Project Overview

The **Creating a Mutual Fund Plan with Python** project is a financial analytics application designed to help investors build and evaluate diversified mutual fund portfolios using historical market data. The project leverages Python for data collection, preprocessing, portfolio construction, risk analysis, and performance visualization.

The application enables users to simulate different investment strategies, compare portfolio performance, analyze risk-adjusted returns, and generate personalized investment recommendations based on their financial goals and risk tolerance.

---

## Project Objectives

The main objectives of this project are:

- Analyze historical mutual fund performance.
- Build diversified investment portfolios.
- Calculate portfolio return and investment risk.
- Evaluate portfolios using financial performance metrics.
- Perform Monte Carlo simulations for future projections.
- Optimize portfolio allocation using Modern Portfolio Theory.
- Provide interactive visualizations and investment recommendations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- SciPy
- Scikit-learn (Optional)
- yFinance / Yahoo Finance API
- Streamlit (Optional Dashboard)

---

## Project Workflow

### Data Collection

Historical mutual fund data is collected from financial data providers such as:

- Yahoo Finance
- Alpha Vantage
- AMFI
- Other financial APIs

The dataset contains:

- Net Asset Value (NAV)
- Historical Prices
- Daily Returns
- Monthly Returns
- Expense Ratio
- Dividend Information

---

### Data Cleaning

The preprocessing stage includes:

- Removing missing values
- Eliminating duplicate records
- Converting date columns
- Sorting chronological records
- Resampling daily/monthly data
- Calculating percentage returns

---

### Feature Engineering

Several financial indicators are calculated:

- Daily Return
- Monthly Return
- Annual Return
- Annualized Return
- Cumulative Return
- Portfolio Return
- Portfolio Volatility
- Standard Deviation
- Expense Ratio

---

### Exploratory Data Analysis (EDA)

EDA is performed to understand fund behavior using various visualizations.

The analysis includes:

- NAV Trend
- Return Distribution
- Volatility Comparison
- Correlation Matrix
- Cumulative Returns
- Expense Ratio Comparison

---

## Portfolio Construction

Users can customize:

- Initial Investment Amount
- Investment Horizon
- Risk Tolerance
- Mutual Fund Allocation

Example Portfolio:

- Fund A → 50%
- Fund B → 30%
- Fund C → 20%

The portfolio return is calculated using weighted historical returns.

---

## Risk & Return Analysis

The project evaluates investments using several financial metrics.

### Expected Return

Measures the average portfolio return.

---

### Portfolio Risk

Measured using standard deviation (volatility).

---

### Sharpe Ratio

Measures risk-adjusted performance.

Higher Sharpe Ratio indicates better investment efficiency.

---

### Sortino Ratio

Measures downside risk instead of total volatility.

Useful for conservative investors.

---

### Monte Carlo Simulation

Simulates thousands of future portfolio scenarios to estimate:

- Best Case
- Average Case
- Worst Case
- Probability Distribution

---

### Portfolio Optimization

Mean-Variance Optimization is used to identify the optimal portfolio that provides:

- Maximum Return
- Minimum Risk
- Efficient Asset Allocation

---

## Visualizations

The project generates multiple financial charts including:

### Portfolio Performance

- Portfolio Growth Curve
- Benchmark Comparison

### Risk Analysis

- Risk vs Return Scatter Plot
- Efficient Frontier

### Portfolio Composition

- Pie Chart
- Allocation Breakdown

### Correlation Analysis

- Heatmap

### Simulation

- Monte Carlo Simulation Graph

---

## Interactive Dashboard

The application can be deployed using **Streamlit** to provide:

- Investment Amount Selection
- Portfolio Allocation Adjustment
- Risk Profile Selection
- Time Horizon Selection
- Dynamic Performance Charts
- Investment Summary

---

## Key Features

- Historical Mutual Fund Analysis
- Portfolio Construction
- Investment Allocation
- Risk Assessment
- Portfolio Optimization
- Monte Carlo Simulation
- Interactive Dashboard
- Financial Reporting

---

## Key Performance Indicators (KPIs)

- Portfolio Return
- Annualized Return
- Portfolio Volatility
- Sharpe Ratio
- Sortino Ratio
- Expense Ratio
- Diversification Score
- Maximum Drawdown

---

## Key Insights

### Diversification

Diversified portfolios consistently reduce investment risk compared to investing in a single mutual fund.

---

### Risk vs Return

Higher returns generally come with higher volatility.

Risk-adjusted metrics provide a more accurate measure of portfolio quality.

---

### Sharpe Ratio

Portfolios with higher Sharpe Ratios deliver superior returns per unit of risk.

---

### Expense Ratio

Lower expense ratios contribute significantly to long-term wealth creation.

---

### Monte Carlo Analysis

Future investment performance is uncertain, making simulation valuable for understanding potential outcomes.

---

## Business Recommendations

Based on the analysis:

- Diversify investments across multiple mutual funds.
- Choose portfolios with higher Sharpe Ratios.
- Periodically rebalance investments.
- Consider expense ratios before selecting funds.
- Align portfolio allocation with individual risk tolerance.
- Use Monte Carlo simulations to evaluate future uncertainty.

---

## Project Structure

```text
Mutual-Fund-Plan-With-Python/
│
├── mutual_fund_plan.ipynb
├── README.md
```

---

## Python Libraries Used

- pandas
- numpy
- matplotlib
- plotly
- scipy
- yfinance
- streamlit
- seaborn (Optional)

---

## Financial Concepts Covered

- Portfolio Diversification
- Asset Allocation
- Modern Portfolio Theory
- Risk Management
- Portfolio Optimization
- Volatility Analysis
- Monte Carlo Simulation
- Risk-Adjusted Return

---

## Business Value

This project helps:

- Individual Investors
- Wealth Managers
- Financial Advisors
- Investment Firms

by enabling them to:

- Build optimized portfolios
- Analyze investment risk
- Compare mutual funds
- Simulate future returns
- Make informed investment decisions

---

## Learning Outcomes

This project strengthened my skills in:

- Financial Data Analysis
- Python Programming
- Portfolio Analytics
- Data Visualization
- Statistical Analysis
- Investment Risk Assessment
- Monte Carlo Simulation
- Streamlit Dashboard Development

---

## Future Enhancements

- Live Mutual Fund NAV Updates
- SIP & SWP Calculator
- Goal-Based Investment Planning
- Tax-Efficient Portfolio Suggestions
- AI-Based Mutual Fund Recommendation System
- Portfolio Rebalancing Alerts
- Email Report Generation
- Multi-Asset Portfolio Support (Stocks, ETFs, Bonds)

---

## Author

**Kashish Gupta**

M.Tech (Computer Science)

AI/ML | Data Analytics | Python | Power BI | Excel


---

## ⭐ Support

If you found this project useful, please ⭐ the repository and feel free to contribute or provide feedback!
