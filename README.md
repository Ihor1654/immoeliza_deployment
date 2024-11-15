![Python](https://img.shields.io/badge/Made_with-Python-blue?logo=python&labelColor=%23778899&color=%233776AB)
![Pandas](https://img.shields.io/badge/uses-Pandas-blue?logo=pandas&labelColor=%23778899&color=%23150458)
![Fastapi](https://img.shields.io/badge/uses-Fast_api-violet?logo=fastapi&color=%23009688)
![HTML5](https://img.shields.io/badge/Made_with-HTML-blue?logo=html5&labelColor=%23778899&color=%23E34F26)
![Bootstrap](https://img.shields.io/badge/uses-bootstrap-violet?logo=bootstrap&labelColor=%23778899&color=%237952B3)


🔎 **Project Overview**
This web service provides the user with the ability to predict real estate prices in Belgium using one of the available models. The primary objective is to provide accurate price estimates for properties based on their features like location, area, number of rooms, etc.

🤖 **Models**

Prediction is possible using one of the following models:
- XGBoost
- Linear Regression
- Random Forest

**Models stats**


The following metrics were used to evaluate model quality: Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and R².

The best-performing model, XGBoost, achieved an R² score of 0.75 on the test set, indicating that it can explain 75% of the variance in property prices.

The evaluation results of the models are presented in the table below:

```

| Model           | MAE         |   RMSE         | R2    |
|                 |             |                |       |
| LinearRegressor | 66,670.13   | 93,728.26      | 0.67  |
| XGBoost         | 56,741.12   | 82,076.52      | 0.75  |
| Random Forest   | 70,506.67   | 101,496.22     | 0.62  |


```
