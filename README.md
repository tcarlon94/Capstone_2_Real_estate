# Capstone_2_Real_estate

This project aims to predict future home prices by location using real estate data from Zillow. The goal is to provide insights for individuals and real estate investors interested in understanding future housing market trends.

The project begins with a data wrangling phase where raw real estate data is processed and cleaned. This involves handling missing values, dealing with outliers, combining data from 4 CSVs, and preparing the data for further analysis and modeling.

Following data preparation, EDA is performed to understand the characteristics of the dataset. This includes visualizing the distribution of home prices and related features, identifying correlations, and exploring trends based on geographical location.

Next, the model training phase involves exploring and training various regression models to predict home prices. Different algorithms, such as Linear Regression, Ridge/Lasso Regression, Gradient Boost Regressor, and ARIMA are evaluated for their predictive performance.

The Ridge Reegression model was identified as the best-performing model, achieving a test R^2 score of 88% and a RMSE $29,000.

Finally, the trained model is used to predict home prices for the next 5 years based on location. This includes generating visualizations that illustrate the projected future home prices across different geographical areas.

The project provides key predictions for home prices by location for the next five years. These predictions are derived from:

Historical trends and patterns observed in the real estate data.
The robust predictive power of the Gradient Boost Regressor model.
Further details, including specific visualizations of the predicted home prices, are available within the project's analysis outputs.
```
