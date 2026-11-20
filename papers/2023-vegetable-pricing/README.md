# Multivariate forecasting and optimisation for vegetable pricing and replenishment

**2023 undergraduate mathematical modelling report · Team project including Junjia Cao**

Original Chinese title: **基于多元预测和优化模型的蔬菜类商品的自动定价与补货决策**

## Overview

This report studies how a fresh-food retailer can use historical sales data to guide replenishment and pricing decisions while accounting for demand variation, perishability, and profit.

## Method

- Visualisation and correlation analysis for item and category demand.
- **Shapiro–Wilk**, **Pearson**, and **Spearman** analysis for distribution and relationship checks.
- **Holt–Winters** and **ARIMA** for short-term demand forecasting.
- **Simulated annealing** for category-level replenishment and pricing optimisation.
- **Genetic algorithms** for item-level daily replenishment decisions.
- Market, consumer, and supply-chain analysis for additional decision support.

## Reported Approach

The work first analyses category and item relationships, then forecasts demand, optimises category-level decisions, and finally produces item-level replenishment and pricing strategies for 29 products on 1 July.

The source report presents these as modelling results. No independent recomputation has been performed for this repository.

## Author Contribution

Junjia Cao was responsible for **all code and mathematical modelling work** in this team project. The report remains a team-authored work; this contribution statement does not imply sole authorship of every part of the manuscript.

## Report and Code

- **Report:** [PDF](paper.pdf), included with permission from the team.
- **2026 implementation:** [Vegetable-Pricing-Replenishment](https://github.com/Cjj040721/Vegetable-Pricing-Replenishment) — a new leakage-aware forecasting and MILP optimisation project with a verified synthetic demo.
- **Historical source package:** Not archived. The new implementation does not claim to reproduce the report's numerical results.
