# Predict-electricity-consumption-and-CO2-emission-of-buildings

# Aim of this project

* The aim of this project was to create predict the electricity consumption and the C02 emissions of buildings : this is a regression problem.<br>
* After clearning up the date, several machine learning models were used to perform regression : <br>
    - linear models : linear regression, using Ridge and Lasso regularization, <br>
    - non linear : Support Vector Machines, <br>
    - and decision tree models : Random Forest, XGBoost, GradientBoostingRegressor <br>

<br>

# Walkthrough the results

* <b>Electricity consumption modelling </b>: best model is linear regression using Lasso regularization (highest R² and lowest RMSE): <br>
![Capture d’écran 2023-05-19 à 16 33 38](https://github.com/mochan42/Predict-electricity-consumption-and-CO2-emission-of-buildings/assets/107719618/32a5ae55-271e-420f-977d-2430379093ab)


* <b>CO2 Emissions modelling </b>: best model is GradientBoostingRegressor : best model is GradientBoostingRegressor(highest R² and lowest RMSE): <br>
![Capture d’écran 2023-05-19 à 16 37 00](https://github.com/mochan42/Predict-electricity-consumption-and-CO2-emission-of-buildings/assets/107719618/1cfed39a-5e82-4296-a361-180ddac528ee)
