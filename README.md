This project is a small notebook on a two-stock portfolio analysis that implements core ideas from Modern Portfolio Theory (Markowitz) and the CAPM “market portfolio” intuition.

Given **two equity tickers**, it:
- downloads the last ~1 year of daily prices,
- computes annualized return/risk statistics,
- builds the **full set of two-asset portfolio combinations**,
- finds the **Global Minimum Variance Portfolio (GMVP)**,
- finds the **Optimum (Tangency) Market Portfolio (OMP)** that maximizes the Sharpe ratio vs a risk-free rate,
- optionally plots the **efficient frontier** and the **capital allocation line**.`CAPM.ipynb`
