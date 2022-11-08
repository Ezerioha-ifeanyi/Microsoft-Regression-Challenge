# Microsoft-Regression-Challenge

Predicting the selling price of a residential property depends on a number of factors, including the property age, availability of local amenities, and location.

- In this challenge, you will use a dataset of real estate sales transactions to predict the price-per-unit of a property based on its features. The price-per-unit in this data is based on a unit measurement of 3.3 square meters.

- Citation: The data used in this exercise originates from the following study:

- Yeh, I. C., & Hsu, T. K. (2018). Building real estate valuation models with comparative approach through case-based reasoning. Applied Soft Computing, 65, 260-271.

- It was obtained from the UCI dataset repository (Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science).


The data consists of the following variables:

- transaction_date - the transaction date (for example, 2013.250=2013 March, 2013.500=2013 June, etc.)
- house_age - the house age (in years)
- transit_distance - the distance to the nearest light rail station (in meters)
- local_convenience_stores - the number of convenience stores within walking distance
- latitude - the geographic coordinate, latitude
- longitude - the geographic coordinate, longitude
- price_per_unit house price of unit area (3.3 square meters)


The challenge is to explore and prepare the data, identify predictive features that will help predict the price_per_unit label, and train a regression model that achieves the lowest Root Mean Square Error (RMSE) you can achieve (which must be less than 7) when evaluated against a test subset of data.
