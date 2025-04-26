# Equity Portfolio Optimization (R)

This project simulates portfolio rebalancing strategies using historical stock price data for a $5 million equity fund. The objective is to evaluate buy-and-hold vs. periodic rebalancing strategies based on daily market-to-market (MTM) values across 10 selected tech stocks.

> Completed as part of the **Data Analytics with R** course at NJIT.

---

## Dataset
- **Source**: Simulated time series data for 10 publicly traded tech stocks
- **Structure**: Daily stock prices throughout 2018 (250+ trading days)
- **Format**: CSV

---

## Project Goals
- Simulate market value changes using stock returns
- Analyze and compare rebalancing strategies:
  - **Buy and Hold**
  - **Quarterly Rebalancing**
  - **Annual Rebalancing**
- Optimize rebalancing based on dividends and MTM performance

---

## Tools & Techniques
- **R**: `tidyverse`, `lubridate`, `ggplot2`
- Portfolio return calculations
- Cumulative return and drawdown analysis
- Time series visualization

---

## Sample Output

| Strategy               | Final Portfolio Value |
|------------------------|------------------------|
| Buy & Hold             | $5.78M                 |
| Quarterly Rebalance    | $5.95M                 |
| Annual Rebalance       | $5.81M                 |

---

## Project Structure

```
equity-portfolio-optimization-r/
├── equity_portfolio_management_project.ipynb   # Main notebook
├── data/                                       # CSV time series data
├── outputs/                                    # Charts, results
└── README.md                                   # Project overview
```

---

## Key Learnings
- Rebalancing frequency impacts long-term portfolio performance
- Data visualization helps evaluate strategy volatility
- Portfolio optimization requires balancing returns vs. transaction costs

---

## Author

**Anastasiya Kotelnikova**  
MS Data Science Student @ NJIT  
[GitHub](https://github.com/AnastasiyaKotelnikova) • [LinkedIn][(https://www.linkedin.com/in/anastasiyakotelnikova/)]

