## Project-for-HSBC Market Risk

**Project Description**

The purpose of this project is to present basic quantitative tools used for VaR risk projections. This
involves definitions and comments on the most common VaR estimation methods like:

- Historical VaR
- Filtered Historical VaR
- Gaussian VaR

[Note: this project briefing is written before all courses were deliverd, so it is ok to stick to methods that
were discussed.]

The estimators should be applied to recent market data, i.e. daily (close price) returns for selected four
major stock index returns (e.g. DAX, FTSE, WIG, S&P, NIKKEI). VaR at level 1% should be computed using
different lookback/estimation periods (e.g. n=250,500) for multiple days in 2020. The performance of
each estimator should be assessed in reference to COVID-19 induced market shocks. Evaluation should
include backtesting results, i.e. 1-day rolling-window backtest that is aligned with regulatory backtest
concept.

**Data**

Data can be downloaded from a publicly available data source (e.g. Yahoo Finance). We recommend
downloading daily closing prices and using this to create daily relative returns. The data period should be
the last full 5 years.

**Questions / Requirements**

Student is required to complete the following steps:
- Download and describe the downloaded data. Compute and graphically present return rated for the
period considered and comment on what real world events influence the data (eg. Covid19, War,
elections, etc). The I.I.D. data property (or lack of it) should be discussed and tested.
- Propose a couple of daily VaR (at level 1%) estimators, discuss related mathematical background,
and estimation methods pros and cons. Different lookback (learning) periods should be used, and
different estimation techniques should be proposed.
- Using the introduced VaR models the risk for all business days in the period should be computed and
graphically presented.
- Backtesting should be used to evaluate each model's performance. The performance should be
assessed in reference to COVID-19 data and differences should be commented on (e.g. resulting from
size of lookback period or the used methodology). One could also consider different performance
metrics based e.g. on PIT-based backtests or mean quantile score evaluation.
- Identify the best estimator and discuss it. Potential flaws should be outlined, and potential
enhancements could be proposed
