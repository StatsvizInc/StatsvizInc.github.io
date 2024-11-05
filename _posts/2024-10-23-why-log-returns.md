---
layout: post
title: "The two reasons to use log returns"
author: StatsViz Inc. 
tags: [concept]
---

## They add up
* Log returns allow us to assess cumulative returns over time by simply adding individual log returns. 
* This is particularly useful in trading charts for analyzing returns over longer periods, which can be beneficial for tracking assets like the VIX Index.
* Simple returns require more complex compounding, making them harder to work with in time-series contexts.

## They normalize extreme values
* Log returns help transform financial data closer to a normal distribution (bell-shaped), which can make trading tools and statistical models easier to interpret 
* Extreme values and outliers tend to be moderated compared to simple returns, which is crucial when visualizing trading charts.
* Log returns interpret price changes proportionally rather than absolutely. For instance, a stock’s move from $100 to $110 has the same log return as a move from $200 to $220, making percentage changes more intuitive.

## Summary
Log returns offer a mathematically sound and statistically practical way to analyze asset returns, particularly when analyzing volatile securities, modeling over time, and comparing different assets like stocks, and ETFs. 