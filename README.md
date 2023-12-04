#L50-TOXICITY-PREDICTION-USING-QSAR


To predict the LC50 values, which represent the concentration causing death in 50% of test fish over a 96-hour period, quantitative structure-activity relationship (QSAR) models were developed. The study focused on 908 chemicals and utilized six molecular descriptors: MLOGP (molecular properties), CIC0 (information indices), GATS1i (2D autocorrelations), NdssC (atom-type counts), NdsCH (atom-type counts), and SM1_Dz(Z) (2D matrix-based descriptors).

The LC50 data served as the model response, and various regressor models were employed in the analysis:

K-Nearest Neighbours
Multiple Linear Regression
XGBoost Regressor
Support Vector Machine Regressor
Random Forest Regressor
Bayesian Ridge Regressor
These models aimed to establish a quantitative relationship between the chemical descriptors and the acute aquatic toxicity towards the fish fathead minnow (Pimephales promelas). 

![arch](https://user-images.githubusercontent.com/73905298/152676791-24a6b9d1-2056-4b3b-b64d-8a81ffa1a36e.jpg)


Calculate Predictions, Training time, Prediction time, R squared value, MAE value, RMSE value for every model, save results to csv file and serialize most optimal model using pickle dump.
Dynamically load data into  database by integrating Python with MySQL; Save logging times of code to a database in MySQL.

![l50](https://github.com/vineeth2281/L50-TOXICITY-PREDICTION-USING-QSAR/assets/67580974/dcab8192-b528-4e76-911b-08f9d131ab92)



