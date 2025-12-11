# CO2_Emissions_SVR_Project.
# CO₂ Emission Prediction with SVR

This project applies **Support Vector Regression (SVR)** to make a prediction of a vehicle’s CO₂ emissions in grams per kilometer, based on input variables like engine size, fuel efficiency, and vehicle type, among others.

## Dataset

S. S.

* Engine size of vehicle.
* FuelConsumption_City / Hwy / Comb. (L/100km
* Vehicle Class: (eg, compact, sedan, SUV)

* **CO2 EMISSIONS**

# Method
import

* Preprocessing: standardization of numeric features and one-hot encoding of categorical features.

* Model: $SVR$ with **RBF kernel**, optimized using $GridSearchCV$ over $C$ and $

## Results
On the test set:

*  R²:

* MAE: 22.5

* **MSE:**
Residual and learning curve plots indicate a good fit and a stable generalization, where engine size and fuel consumption are found to be the most prominent predictors.

# How to Run

1. Installing dependencies: These would be "numpy," "pandas," "sc
2. Open a project in Jupyter named
3. Now, point your notebook to your CSV file and run all the cells to reproduce EDA, training, and evaluation. ## Future Work * Include features such as vehicle age, weight, and fuel type. • Use “advanced” model tuning, like those in “Randomized Search CV” and “Bayesian optimization,” and test these models against “tree-based models” such * Use as simple web application (Flask/FastAPI) for carrying out real-time predictions.
