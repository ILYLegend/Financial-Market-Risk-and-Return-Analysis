# Financial Market Risk & Return Analysis

**By:** Armaan Patel  
**Date:** August 2025  

## Overview
This project analyzes the risk-return profile of selected financial assets over a 10-year period (2015–2025).  
Using quantitative finance techniques, I calculated key metrics such as **Annualized Return**, **Volatility**, **Sharpe Ratio**, **Beta**, and **Max Drawdown**, then applied **Modern Portfolio Theory** to construct and optimize investment portfolios.  

An interactive **Tableau dashboard** allows users to explore asset performance, portfolio allocations, and efficient frontiers dynamically.

---

## Files
### CSV Data Files
- `market_data.csv` – Historical daily OHLCV data for all selected assets.
- `market_open_data.csv` – Open price data.
- `market_close_data.csv` – Close price data.
- `asset_metrics.csv` – Metrics for each asset.
- `asset_metrics_clean.csv` – Cleaned metrics for each asset.
- `market_prices_long_clean.csv` – Reformatted market data for Tableau.
- `portfolio_efficient_frontier.csv` – Efficient Frontier points.
- `portfolio_optimal_weights.csv` – Portfolio weight allocations.
- `portfolio_summary.csv` – Portfolio performance summary.
- `portfolio_efficient_frontier_long_clean.csv` – Cleaned Efficient Frontier data.
- `portfolio_optimal_weights_long_clean.csv` – Cleaned portfolio weights.
- `portfolio_summary_clean.csv` – Cleaned portfolio summary.

### Tableau Workbook
- `Financial_Market_Risk_Return.twbx` – Contains all visualizations, dashboards, and calculations.

### Images
- 30-Day Rolling Annualized Volatility — Equal-Weight.png
- correlation_heatmap.png
- cumulative_returns.png
- efficient_frontier.png

---

## Project Goals
- Analyze historical market data for risk-return relationships.
- Calculate and visualize financial performance metrics.
- Construct and optimize portfolios using Modern Portfolio Theory.
- Develop interactive Tableau dashboards for portfolio exploration.
- Create a reusable framework for analyzing other assets and periods.

---

## Tools & Libraries
**Tools:**  
- JupyterLab  
- Tableau  

**Python Libraries:**  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `yfinance`  

---

## Project Summary
Data from **AAPL, MSFT, GOOG, DIA, SPY, BTC-USD, and ETH-USD** was collected from Yahoo Finance for the period **Jan 1, 2015 – Jan 1, 2025**.  

Analysis included:
- Annualized returns and volatility
- Sharpe ratio and beta
- Maximum drawdown
- Correlation heatmaps
- Efficient Frontier & Monte Carlo simulations
- Tangency (Max Sharpe) and Minimum Variance portfolios

The Tableau dashboards allow:
- Risk vs Return exploration
- Efficient Frontier navigation
- Portfolio allocation viewing
- Cumulative performance and drawdown tracking

---

## Key Findings
- **Crypto assets** had the highest returns but also the highest volatility.
- Diversification with equities and index funds improved Sharpe ratios.
- The **tangency portfolio** favored tech stocks and index funds, with minimal crypto.
- Index funds exhibited **lower drawdowns** during downturns.
- **Cryptocurrencies** showed low correlation to equities, offering diversification benefits.

---

## Future Enhancements
- Add bonds, commodities, and sector ETFs.
- Auto-update the risk-free rate using current U.S. Treasury yields.
- Integrate real-time market data.
- Explore advanced optimization models (Black-Litterman, robust optimization).
- Implement predictive modeling for returns and volatility.
- Improve dashboard interactivity for users of any level of financial literacy.

---

## Dashboards
- **Overview Dashboard:** Cumulative performance + risk vs return.
- <img width="1186" height="683" alt="image" src="https://github.com/user-attachments/assets/49a6adcd-381f-41aa-9ee2-8795e9be9d64" />
- **Portfolio Explorer:** Efficient Frontier, allocation, and portfolio metrics.
- <img width="1400" height="802" alt="image" src="https://github.com/user-attachments/assets/f135b4e6-2da3-4436-9930-1543a4e46e4e" />
- **Curated Portfolio:** KPI metrics and weight breakdown.
- <img width="1302" height="300" alt="image" src="https://github.com/user-attachments/assets/7d918b38-1b1b-4bbd-8cf5-ab7c12f4a41d" />

---

## License
This project is released under the MIT License. See `LICENSE` for details.

---

## Contact
**Armaan Patel**  
- LinkedIn: [https://www.linkedin.com/in/armaan-p/](https://www.linkedin.com/in/armaan-p/)
- GitHub: [https://github.com/ilylegend](https://github.com/ilylegend)
