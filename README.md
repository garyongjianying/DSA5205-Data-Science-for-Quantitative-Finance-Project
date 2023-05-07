# DSA5205-Data-Science-for-Quantitative-Finance-Project
DSA5205 Data Science for Quantitative Finance Project (in R)


Aim of project: Use of limited lookback portfolio optimization framework built upon Markowitz model / Michaud's Resampled Efficiency method.
Metrics: Value at Risk (VaR) and Expected Shortfall (ES) assuming multivariate skewed student t-distribution fitted to all avaialble returns data at and before the portfolio selection date.

Our portfolio selection framework is meant to be easily interpretable and applied by a typical
retail investor. To mimic practices common to retail investors in our methodology, the
following assumptions are made:
1. Start investing on the first trading day of the second half of 2021, i.e. 1 July 2021
2. Risk-free rate is fixed at 2% per annum
4
3. Brokerage fee is 0.2% of value traded
4. Starting value of the portfolio is $10,000
5. Portfolio is rebalanced at the end of every month to manage transaction costs
6. No short-selling
7. Fractional investing (partial units) is allowed
