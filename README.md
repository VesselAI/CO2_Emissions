# CO2_Emissions

## Description
This repository contains code related to the experimentation and evaluation of various machine learning models on a specific dataset. The models were tested to analyze their performance and effectiveness in solving a particular task.

## Results
The performance metrics of various machine learning algorithms on the dataset are presented below:

| Algorithm                    | R2 (%) | MAE   | NRMSE | SMBE    |
|------------------------------|--------|-------|-------|---------|
| Linear Regression            | 78.19  | 0.529 | 1.009 | 3.767   |
| Ridge Regression             | 78.19  | 0.529 | 1.009 | 3.597   |
| LASSO                        | 74.31  | 0.457 | 1.095 | 3.380   |
| SVR                          | 87.65  | 0.279 | 0.759 | 5.473   |
| AdaBoostRegressor            | 71.35  | 0.888 | 1.156 | -204.786|
| BaggingRegressor             | 93.61  | 0.201 | 0.546 | 0.918   |
| ExtraTreesRegressor          | 93.98  | 0.195 | 0.530 | 0.827   |
| GradientBoostingRegressor    | 92.28  | 0.250 | 0.600 | 3.078   |
| RandomForestRegressor        | 92.68  | 0.213 | 0.584 | 0.153   |
| Voting Regressor             | 90.76  | 0.305 | 0.656 | -23.01  |
| DecisionTree Regressor       | 85.06  | 0.286 | 0.835 | -0.802  |
| MLPRegressor                 | 94.11  | 0.197 | 0.524 | 1.358   |
| DNN                          | 90.17  | 0.253 | 0.677 | 5.152   |
| LightGBM Regressor           | 90.67  | 0.265 | 0.659 | 8.417   |


## Academic Paper
For more detailed analysis, experimental setup, and discussions on the results, please refer to our academic paper titled "Comparison of Machine Learning Algorithms For Predicting CO2 Emissions in the maritime domain" by Author(s) https://ieeexplore.ieee.org/abstract/document/10345936. The paper provides comprehensive insights into the methodology, findings, and implications of the experimentation conducted.
