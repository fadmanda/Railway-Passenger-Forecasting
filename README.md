# Railway Passenger Forecasting in Jabodetabek Region

## Project Overview

This project analyzes monthly railway passenger data in the Jabodetabek region from 2015 to 2019. It explores long-term trends and seasonal patterns, then compares forecasting methods using 2019 as the test period.

This is a reconstructed portfolio project inspired by an earlier academic project. The current analysis uses the dataset available for this portfolio and does not claim to reproduce the original assignment results.

## Objectives

* Explore monthly and yearly passenger trends.
* Examine seasonal patterns using time series decomposition.
* Compare forecasting methods using MAE, RMSE, and MAPE.

## Dataset

* **Region:** Jabodetabek
* **Period:** January 2015 – December 2019
* **Frequency:** Monthly
* **Measure:** Railway passengers, in thousand people

## Tools & Libraries

* Python
* Pandas
* Matplotlib
* Statsmodels
* Scikit-learn
* Google Colab

## Methodology

1. Data loading, inspection, and cleaning
2. Data reshaping and monthly date indexing
3. Exploratory Data Analysis (EDA)
4. Monthly seasonality analysis
5. Time series decomposition
6. Train-test split (2015–2018 training, 2019 testing)
7. Seasonal Naive forecasting
8. Holt-Winters forecasting
9. Model evaluation using MAE, RMSE, and MAPE

## Key Findings

* Passenger volume showed an overall increasing trend during 2015–2019.
* Monthly passenger volume varied across calendar months.
* On the 2019 test period, Seasonal Naive produced lower MAE, RMSE, and MAPE than the additive Holt-Winters model.

## Project Files

* `Railway_Passenger_Forecasting.ipynb` — notebook containing the analysis and forecasting workflow.
* `railway_passenger_jabodetabek.xlsx` — monthly passenger dataset used in the project.

## Limitations

The model comparison uses a single 12-month test period. Results describe performance on this test set and may not generalize to other time periods. The analysis is exploratory and does not establish the causes of passenger-volume changes.

## Author

[Fadhilla]
