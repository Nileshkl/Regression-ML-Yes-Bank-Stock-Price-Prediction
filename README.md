# :star: Yes Bank Stock Price Prediction :star:
## :star: Regression ML Capstone Project:star:
![Yesbanklogo](https://github.com/Nileshkl/Regression-ML-Yes-Bank-Stock-Price-Prediction/blob/511fdbaeb7bc2b124defdeaa3650d8b4963d2c7e/yes-bank-logo-vector%20(1).png)

---
## Project Summary
This project's primary objective was to investigate the repercussions of a fraud case linked to Rana Kapoor on the stock prices of Yes Bank, a prominent player in the Indian financial sector. The dataset employed for this analysis encompassed monthly stock prices of Yes Bank from its inception, including metrics like closing, opening, highest, and lowest stock prices.

Data Description

- **Date** - Date of Record
- **Open** - Opening Price
- **High** - Highest price of the day
- **Low**  - Lowest price of the day
- **Close** - Last price at closing of market

# Investigating the Impact of the Rana Kapoor Fraud Case on Yes Bank Stock Prices

## Overview

This project was dedicated to comprehensively examining the repercussions of the Rana Kapoor fraud case on the stock prices of Yes Bank, a significant player in the Indian financial sector. The analysis involved a dataset comprising monthly stock prices of Yes Bank from its inception, encompassing essential metrics such as closing, opening, highest, and lowest stock prices.

This project was dedicated to comprehensively examining the repercussions of the Rana Kapoor fraud case on the stock prices of Yes Bank, a significant player in the Indian financial sector. The analysis involved a dataset comprising monthly stock prices of Yes Bank from its inception, encompassing essential metrics such as closing, opening, highest, and lowest stock prices.

## Key Steps Involved

The project followed a structured approach, including the following key steps:

1. **Data Preprocessing:** Initial data preparation and cleaning to ensure data quality.

2. **Data Cleaning:** Addressing missing values, handling anomalies, and ensuring data integrity.

3. **Data Duplication Management:** Identifying and managing duplicate data points if present.

4. **Outlier Handling:** Identifying and addressing outliers in the dataset.

5. **Feature Transformation:** Preparing features for modeling, which may involve scaling, normalization, or other transformations.

6. **Exploratory Data Analysis:** Investigating the data to understand patterns, trends, and potential insights.

7. **Categorical Column Encoding:** Preparing categorical data for modeling through encoding techniques.

## Algorithm Selection

For predicting the closing price of Yes Bank's stock, several regression algorithms were considered:

a. **Linear Regression:** A fundamental regression model for establishing linear relationships.

b. **Ridge Regression:** A regularization technique to mitigate overfitting.

c. **Random Forest Regressor:** An ensemble method combining decision trees for improved accuracy.

d. **XGBoost Regressor:** A gradient boosting algorithm known for its predictive power.

Each of these algorithms was meticulously trained and evaluated to determine the best-performing model.


## Models and Predictive Analysis

To predict the closing price of Yes Bank's stock, three distinct models were developed: Ridge Regression, Random Forest, and XGBoost Regressor. These models were meticulously trained using historical stock price data, in combination with various features, including mean values of Open, High, and Low stock prices. Additionally, temporal trends and patterns were captured by engineering features involving lagged variables. Model performance was evaluated using metrics such as Root Mean Squared Error (RMSE), adjusted R-squared, and R-squared (R2) scores. Remarkably, the XGBoost Regressor outperformed the other models, demonstrating a high R2 score and adjusted R2 score.

## Feature Importance

The heart of the analysis revolved around identifying any observable patterns or alterations in Yes Bank's stock prices in relation to the Rana Kapoor fraud case. The feature importance rankings provided by the XGBoost model played a pivotal role in pinpointing the critical factors influencing stock prices.

## Contribution and Insights

In summary, this project aimed to contribute to a deeper understanding of the intricate relationship between the Rana Kapoor fraud case and the dynamics of Yes Bank's stock prices. Furthermore, it sought to explore the potential of predictive modeling in the field of finance. The insights and findings derived from this endeavor hold significance for a broad spectrum of stakeholders, including investors, financial analysts, and decision-makers. These insights can guide them in making more informed decisions related to investments and business strategies involving Yes Bank's stock.

## Conclusion
Our objective was to predict Yes Bank's monthly closing stock price amidst the backdrop of the 2018 Rana Kapoor fraud case. Among Ridge Regression, Random Forest, and XGBoost Regressor models, XGBoost stood out with an impressive R2 score of 0.97.

Data visualization highlighted the fraud case's impact, showing a sharp price decline. Feature engineering, including lag features and log transformations, improved model accuracy.

The most influential features were 'OHL,' 'lag1,' 'lag2,' 'lag12,' 'lag9,' 'lag4,' 'lag6,' and 'lag11.' Incorporating daily data and external factors could enhance predictions, while time series models like ARIMA and LSTM are promising.

Our high-precision model is ready for deployment, aiding strategic financial decision-making.

Feel free to contribute, report issues, or ask questions. Happy coding!

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nileshkumar-lavand/)
