# Dynamic_Pricing_Strategy

![Dymamic pricing image](https://github.com/user-attachments/assets/79c5a7f9-17e5-4f7c-aae2-c7affb5bafdd)

## Table of Cotents
- [Project Overview](#project-overview)
- [Project Objectives](#project-objective)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-EDA)
- [Profit Margin](#profit-margin)
- [Temporal Analysis](#temporal-analysis)
- [Feature Engineering](#feature-engineering)
- [Demand Forecasting](#demand-forecasting)
- [Price Optimization](#price-optimization)

## Project Overview
Develop a dynamic Pricing model that can effectively adjusts prices in E-commerce applications based on real-time demand, competitor prices, and Inventory levels to enhance profit maximization, customer experience, prompt decision making. Throughout the project, I utilized advanced data science techniques to understand data-driven pricing strategies and build predictive models.

## Project Objectives
The primary objective of this project is to:
-	Build a Demand Forecasting Model: Develop a model to forecast the demand for company’s products, this should reduce holding costs by optimizing inventory levels-based o demand forecasts.
- Implement a Dynamic Pricing Model: Develop a dynamic pricing model that considers demand, competitor prices, ad inventory levels to adjust prices automatically
- Optimize profit Margis: Ensure that the dynamic pricing strategy maximizes profit margins while remaining competitive I the market.

## Exploratory Data Analysis (EDA)
- Univariate Analysis: Exploring each features individually.
- Bivariate Analysis: Exploring two features against each others.

## Profit Margin
I looked at what product categories generated the most/least profits in terms of Average profit margin/Total profit margin for all the sales made.
After visualizing it using the bar plot, I noticed that in terms of Total profit margin per category, Electronics and clothing generate the similar amount of profit which in turn is the most profit, while Home & Gardens generate the least profit. In terms of Average profit margin per category, all three product categories have similar profit margins

## Temporal Analysis
In temporal analysis, I had to check if there are some seasonality’s in the dataset, if some of the parameters changes with time. For example, does sales demand increase during Christmas period or any other festive period. 
After undergoing temporal analysis, it shows there are no significant seasonality’s in the data, except for just price fluctuations but I also noticed one key thing where the Average Weekly Selling price is always (18 - 20) % lower than our competitors’ prices

## Feature Engineering
In this section, I prepared my dataset for modelling by dividing the data into train and test dataset. All dataset below 2023 was placed into trainset while all dataset 2023 and above was placed under test set.

## Demand Forecasting
I went on to build a model called the Exponential smoothing to forecast demand and wet to evaluate the model on three parameter, RMSE (root mean squared error), MAE (mean absolute error), MAPE (mean absolute percentage error). MAPE gave an output of 11% which shows how far the values are from the original. This mean our model is performing at 89% accuracy which is performing at a good level.

## Price Optimization
In this section, I created a model to optimize prices and price competitiveness against your competitor prices.
Comparing the usual prices against the optimal prices for all product categories, we can see that profits has increased drastically. For the price differences between our prices and our competitor prices for all product categories, we have been able to reduce the gap between the prices, so we don’t make too many losses as before and to be able to improve our profit.
In most cases our prices mostly never go above our competitor prices except for Usual vs Optimal Average Price Difference for Home & Garden where prices going below zero (0) shows our prices are higher for Home & Garden than the competitor prices.

