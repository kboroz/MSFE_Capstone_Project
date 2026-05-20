# MSFE_Capstone_Project

The current project study intends to assess how varying inter- and intracorrelations between major international equity markets evolve across time horizons and market states,
and form the basis for advanced factor-based investing strategies. Earlier studies (Bae
& Elkamhi 2021; Goetzman 2001) focused on the impact and diversifiaction benefits of
correlation based investemnt strategies (Narayan et al. 2023). 

We calculate daily, 1-week, 2-week, 3-week, and 4-week returns and correlations for the following indices: S&P 500,
B3-Bovespa, EURO STOXX 50, FTSE 100, FTSE/JSE Top 40, Nikkei 225, and ASX 50.
The sample period of 10 years is chosen as the longest common sample across the indices.

Since temporal dislocations due to non-synchronous trading hours may bias short-horizon
comovements, we will also investigate how correlations change as the differencing period
increases, and whether correlations are higher during crises. Additionally, we extend our
feature space by introducing variation of the Correlation Determinant 
(see Tumminello et al. 2010) to robustify the estimation of the dependence structure against noise. We are particularly
interested in North–South differences across global markets and time zones. 

A corollary to the problem is the importance of diversification and hedging: if correlations within
the portfolio increase meaningfully at longer time horizons or in stress regimes, daily
correlation-based portfolios are not sufficiently diversified and may underperform when
protection is needed. We hope to separate assets by statistical behavior, and test whether we can produce a more stable allocation
than other methods based on noisy covariance estimates. Our project implementation
will use publicly available historical market data. 

The end-to-end project (data collection, EDA, correlation estimation, asset allocation, comparison of portfolio construction
methods) will be implemented in Python.
