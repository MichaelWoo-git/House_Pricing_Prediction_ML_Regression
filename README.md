# Project Name: House_Pricing_Prediction_ML_Regression
#### Jupyter Notebook Name: Applied_Regression_Techniques_and_Analysis.ipynb

__Description__:
Competition of predicting house pricing when given 79 explanatory varibles describing every aspect of residential homes in Ames, Iowa. My task was to predict the final price of each home. 

In order to acheive that, I did the following:
* __Cleaned and Prepared the data__
    * Handled outliers and ensure that no null values were present in the dataset
* __Feature Selection and Engineering__
    * Used statistical methods (_Spearman Correlation_, _Scoring Function_,  _Random Forest Feature Importance_) to choose the best features and reduced
    * As for Engineering, _Hot Encoding_ transformations of the categorical features chosen, and _Binning_ and _Logarithmic_ transformations on numerical features chosen
* __Evaluation Regression Models__
    * Models that were used were the following: _Random Forest Regressor_, _Support Vector Regressor_, _Gradient Boosting Regressor_
    * Compared them previous features that were used prior to feature selection and engineering
    * Regression Metrics (MAE, MSE, RMSE, RS^2)
    * SHAP Plots
    

### Visuals

### Metrics of the Models

![metrics](/Screenshots/metrics.JPG)

### Model Summary

![models](/Screenshots/model_comparison.JPG)

### SHAP Plot of Features

![shap](/Screenshots/shap.JPG)
