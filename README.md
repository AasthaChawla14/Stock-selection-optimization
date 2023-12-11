# Stock-selection-optimization

The project aims to create a more manageable and cost-effective index fund that still closely follows the NASDAQ-100 index by carefully selecting a subset of stocks based on their similarities, and then optimizing the buying strategy for those selected stocks. The success of this fund will be assessed by comparing its performance to the actual NASDAQ-100 index.

Background:
There are two main approaches in managing stock portfolios: 'active' and 'passive'. The 'passive' strategy commonly involves creating an 'index fund' that mirrors the movements of a broad market index.

Objective of the Project:
The goal of this project is to create an index fund that tracks the NASDAQ-100 index. An index fund is essentially a portfolio of stocks that aims to replicate the performance of a specific market index.

Challenges with Directly Mimicking the Index:
One way to create an index fund is by purchasing all the stocks in the index with the same weights. However, this is impractical and expensive due to the large number of stocks (n) in the index.

Proposed Solution:
Instead of directly purchasing all stocks in the index, the project aims to create an index fund with a smaller number of stocks (m) that still accurately tracks the NASDAQ-100 index.

Approach:
The process involves several steps. First, an integer program will be formulated. This program selects exactly 'm' out of 'n' stocks for the portfolio based on a 'similarity matrix'. This matrix indicates how similar each stock is to every other stock, using metrics like correlation. A linear program will be solved to determine how many shares of each selected stock to buy for the portfolio.

Evaluation:
The performance of the index fund will be evaluated by comparing it to the NASDAQ-100 index, using data that was not used during the fund creation (out-of-sample).

Parameter Exploration:
The project will explore the fund's performance for various values of 'm', representing different portfolio sizes.
