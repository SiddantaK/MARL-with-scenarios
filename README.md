# Multi-Agent Reinforcement Learning for Liquidation Strategy Analysis

Source code for paper: Extension of Multi-agent reinforcement learning for liquidation strategy analysis for Optimistic Bull and Pessimistic Bear.

# For Implemention of this code, You can mostly look on Optimistic.ipynb, Optimistic.py and Pessimistic.ipynb, Pessimistic.py.

## Abstract

Liquidation is the process of selling a large number of shares of one stock sequentially within a given time frame, taking into consideration the costs arising from market impact and a trader's risk aversion. The main challenge in optimizing liquidation is to find an appropriate modeling system that can incorporate the complexities of the stock market and generate practical trading strategies. This report presents an extension of an existing Multi-Agent Reinforcement Learning (MARL) framework tailored to simulate financial trading environments under optimistic (bull) and pessimistic (bear) scenarios. The MARL system has been tailored to replicate different financial trading scenarios, representing both bull and bear market dynamics. To model different market conditions, the improved framework takes into account metrics including volatility, bid-ask spread, trade volume, and risk aversion. To understand cooperative and competitive dynamics, agents with varying levels of risk aversion are studied in contact with one another. The study offers important new insights into the dynamic behaviors of markets by illuminating how intelligent actors modify their strategies in response to shifting economic situations. This project improves a strategy for selling large amounts of stock without hurting the price. It uses Reinforcement Learning methods to learn the best way to sell, adapting to different market conditions like high or low volatility. It also tests how the strategy holds up in "bullish" and "bearish" markets, helping investors prepare for different situations.

## Proposed Methods

- We theoretically analyze the Almgren and Chriss model and extend its fundamental mechanism so it can be used as the multi-agent trading environment. Our work builds the foundation for future multi-agent environment trading analysis.
- We analyze the MARL by Wenhang Bao & Xiao-Yang Liu in which the cooperative and competitive behaviors between agents by adjusting the reward functions for each agent, which overcomes the limitation of single-agent reinforcement learning algorithms.
- We simulate trading and develop optimal trading strategy with practical constraints by using reinforcement learning method, which shows the capabilities of reinforcement learning methods in solving realistic liquidation problems.
- The study of stock liquidation by considering the optimistic bull or pessimistic bear

## Dependencies

The script has been tested running under Python 3.7.0, with the folowing packages installed:

- `numpy==1.14.5`
- `tensorflow==1.8.0`

## Experiments
