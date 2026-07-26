# Project Description — Tesla Stock Price Analysis

## Project Title
**Stock Price Analysis and Risk Assessment of Tesla Inc. (TSLA) Using Python**

---

## Abstract

This project presents a comprehensive data science analysis of Tesla Inc. (NASDAQ: TSLA),
one of the most actively traded and volatile stocks in the modern financial market.
Conducted as part of the Industrial and Mathematical Finance degree programme at the
Faculty of Science, University of Colombo, this study demonstrates the practical
application of data science techniques to real-world financial data.

Historical daily stock price data spanning from January 2022 to December 2024 was
collected from Yahoo Finance using the `yfinance` Python library, covering approximately
756 trading days. The dataset includes Open, High, Low, Close, and Volume (OHLCV)
fields, which form the foundation of the analysis.

The study begins with Exploratory Data Analysis (EDA) to understand the structure,
distribution, and quality of the data. Key statistical summaries — including mean,
standard deviation, minimum, and maximum closing prices — are computed to establish
baseline insights into Tesla's price behaviour over the analysis period.

Technical analysis is performed through the construction of 50-day and 200-day Simple
Moving Averages (SMA), which are widely used indicators in quantitative finance to
identify medium and long-term price trends. The interaction between these averages
reveals significant market events including Golden Cross and Death Cross patterns,
which are critical signals in momentum-based trading strategies.

Daily returns are calculated using the standard percentage change formula, and their
distribution is examined to assess normality, skewness, and the presence of fat tails —
concepts directly relevant to financial risk modelling and the Mathematical Finance
curriculum. Cumulative return analysis further illustrates the compounded performance
of the stock across the full period.

Quantitative risk assessment is conducted through four key metrics rooted in modern
portfolio theory: the annualised return, annualised volatility, Sharpe Ratio, and
Maximum Drawdown. The Sharpe Ratio, developed by Nobel laureate William F. Sharpe,
measures risk-adjusted return relative to a benchmark risk-free rate of 5% per annum.
Maximum Drawdown captures the most severe peak-to-trough decline, providing insight
into the downside risk exposure of the asset.

All analysis is implemented entirely in Python using industry-standard libraries
including `pandas` for data manipulation, `numpy` for numerical computation,
`matplotlib` and `seaborn` for data visualisation, and `yfinance` for financial
data retrieval. The project is documented in a Jupyter Notebook, ensuring full
reproducibility and transparency of methodology.

This project establishes a strong foundation for more advanced future work, including
multi-asset portfolio optimisation, predictive modelling using machine learning, and
the application of similar analytical frameworks to stocks listed on the Colombo
Stock Exchange (CSE).

---

## Key Topics Covered
- Financial data collection and preprocessing
- Exploratory Data Analysis (EDA)
- Time series visualisation
- Technical indicators (Moving Averages)
- Daily return and cumulative return analysis
- Risk metrics: Sharpe Ratio, Maximum Drawdown, Annualised Volatility
- Python programming for finance

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Jupyter Notebook | Development and documentation environment |
| yfinance | Stock data retrieval from Yahoo Finance |
| pandas | Data manipulation and analysis |
| numpy | Numerical and statistical computation |
| matplotlib | Data visualisation and charting |
| seaborn | Statistical data visualisation |

## Data Source
Yahoo Finance — Tesla Inc. (TSLA), January 2022 to December 2024

## Institution
Faculty of Science, University of Colombo
Department of Mathematics — Industrial and Mathematical Finance
