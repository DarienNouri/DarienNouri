<!-- summary:start -->
I'm a data scientist working on forecasting and alternative data. In summer 2023 I interned at
Citadel, building KPI beat/miss signals from alternative data that went into a live systematic
equity strategy. From 2023 to 2025 I ran PropertizeAI, a real-estate valuation startup.

I'm finishing an MS in Computer Science (Machine Learning) at Georgia Tech in December 2026,
after a BA in Data Science and Computer Science from NYU in 2024.
<!-- summary:end -->

Looking for full-time quant research or data science roles. Based in New York, open to relocating.

[nouri.darien@gmail.com](mailto:nouri.darien@gmail.com) · [LinkedIn](https://www.linkedin.com/in/darien-nouri)

### Kalshi temperature markets vs. a public forecast

[kalshi-forecast-value](https://github.com/DarienNouri/kalshi-forecast-value) is an out-of-sample test of whether prediction-market prices add information to a public weather forecast. Kalshi's NYC daily-high contracts are read as probabilities over temperature bins and compared with NOAA's point forecast, mapped to the same bins by a model fit only on earlier dates. Every price and forecast used was available before its checkpoint, 12 or 6 hours before the settlement day begins.

On 90 held-out days (April to June 2026), the market's Brier loss was 0.694 vs. 0.768 at 12 hours and 0.681 vs. 0.762 at 6 hours. Block-bootstrap intervals for both differences exclude zero. A blend weight fit on earlier dates went to its upper bound of 1: all market, no public forecast. The result is relative to that benchmark, for one station and a spring holdout.

<p><a href="https://github.com/DarienNouri/kalshi-forecast-value"><img src="https://raw.githubusercontent.com/DarienNouri/kalshi-forecast-value/main/reports/assets/holdout-losses.png" width="70%" alt="Kalshi markets vs. a public forecast: mean multiclass Brier loss on 90 held-out dates by method, 12 and 6 hours before the settlement day; lower is better" /></a></p>

### Other projects

- [Bayesian lag selection](https://github.com/DarienNouri/bayesian-factor-selection): spike-and-slab selection over 54 candidate predictors (six NYC data series at lags of 0 to 8 months) for NYC home prices. 311 calls at a 2-month lag and evictions at 6- and 8-month lags had the highest inclusion probabilities.
- [City data and real estate](https://github.com/DarienNouri/alt-data-real-estate-predictions): NYC building complaints, evictions and 100M+ Citi Bike trips as leading indicators for home prices and REIT ETFs, with a scraping, geocoding, MongoDB and Postgres pipeline. NYU research project with Prof. Anasse Bari.
- [Model complexity in pair-spread forecasting](https://github.com/DarienNouri/ml-trading-complexity): NYU team project (2024) comparing linear, tree-ensemble and LSTM models on price and news-sentiment features for stock pairs.
