# Predictive-Asset-Maintenance
The goal is to predict the remaining useful life (RUL) of each engine. The dataset is being provided by [NASA](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan)

The data set includes time-series measurements of various pressures, temperatures, and rotating equipment speeds that for the jet engine. these measurements are typically measured in a commercial modern turbofan engine. All engines are of the same type, but each engine starts with different degrees of initial wear and variations in the manufacturing process, which is unknown to the user. There are three optional settings that can be used to change the performance of each machine. Each engine has 21 sensors collecting different measurements related to the engine state at runtime.

Six different flight conditions were simulated that comprised of a range of values for three
operational conditions: altitude (0–42K ft.), Mach number (0–0.84), and throttle resolver angle (TRA) (20–100).

## Problem Statement

Its a Prediction or Regression problem wherein we have to predict the Remaining Useful Lifecycle for Engines based on the input variables. The problem can also be viewed as Classification problem where we can classify an engine/asset requires maintenance or not. 

## Solution Approach

Evaluate various Regression Techniques along with Hyperparameters Tuning and pick the best model for Regression purpose.
Use the predicted RUL for classifing if an asset requires maintenance or not. 

### Regression Techniques Evaluated 
1. Ramdom Forest Regressor
2. Elastic Net Regressor
3. Support Vector Machine Regressor
4. Gradient Boost Regressor
5. Voting Regressor
6. AdaBoost Regressor
7. HistGradient Boost Regressor
8. XGBoost Regressor
9. Stacking Regressor
10. Deep Learning Model 

### Metrics Used
* R Squared
* Explained Variance
* Mean Absolute Error
* Median Absolute Error
* Max Error
* Mean Squared Error
* Root Mean Squared Error
