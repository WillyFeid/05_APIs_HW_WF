# 05_APIs_HW_WF
Unit 5 Homework: Financial Planning

---

## Overview

In this assignment, we were asked to create two financial analysis tools. First, we created a personal financial planner to vizualize savings portfolios made up of cryptocurrencies and shares. We used this tool to access if they had enough money as an emergency fund. The second tool is used for retirement planning. Based on a time horizon, initial investment, and portfolio weights, we can determine the expected returns at the end of the time horizon.

---

## Technologies

In this assignment, we pulled data from the Alpaca Markets API and the Alternative Free Crypto API to retrieve current crypto and stock prices. We also imported the MCForecastTools toolkit in order to run  Monte Carlo simulationss to project portfolio performance.

## Findings

Based on the current crypto prices, the current portfolio was 62% Crypto and 38% in ETFs/Bonds. Given the users monthly income, and determining that a solid emergency fund would be three months of income, we found that the user does infact have enough savings in case of an emergency at $114528.

For retirement planning, we created a portfolio of 40% Bonds and 60% ETFs, and we want to retire in 30 years. By running a Monte Carlo simmulation, we are able to say with 95% confidence that an initial investment of $20,000 in this portfolio over the next 30 years will be in the range of $77460 and $1268284. 

In addition, a 5 year forecast in a portfolio weighted 90% ETFs and 10% Bonds, there is a 95% chance that your expected returns will be in the range of $18321 and $28215.
