🔎 **Project Overview**
This web service provides the user with the ability to predict real estate prices using one of the available models. The primary objective is to provide accurate price estimates for properties based on their features like location, area, number of rooms, etc.

🤖 **Models**

The project explores several machine learning models, starting with a baseline Extreme Gradient Boosting model and experimenting with other models like Linear Regression and Random Forest Regression. The final model selection is based on performance metrics such as R² score and Mean Squared Error (MSE).

**Models stats**

The best-performing model (XGBoost model) achieved an R² score of 0.75 on the test set, indicating that it can explain 75% of the variance in property prices.


<table>
        <tr><th>Model</th><th>MAE</th><th>RMSE</th><th>R2</th></tr>
        <tr><td>LinearRegressor</td><td>66,670.13</td><td>93,728.26</td><td>0.67</td></tr>
        <tr><td>XGBoost</td><td>56,741.12</td><td>82,076.52</td><td>0.75</td></tr>
        <tr><td>Random Forest</td><td>70,506.67</td><td>101,496.22</td><td>0.62</td></tr>
</table>
