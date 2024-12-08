# Machine-Learning
## Model Implementation
1) Linear Regression
2) Decision Tree Regressor
3) Random Forest Regressor
4) Gradient Boosting Regressor
5) Support Vector Regressor
## Model Evaluation
we train and evaluate all the models Implemented on the test set and calculated the R-squared Score ,Mean Squared Error,Mean Absolute Error

 R-squared: This metric tells us how well the model fits the data. The higher the R-squared value, the better the model explains the variance in the target variable.
 Mean Squared Error: MSE is the average squared difference between predicted and actual values. The smaller the value, the better the model.
 Mean Absolute Error: MAE measures the average absolute difference between predicted and actual values. Lower is better again.

After Checking Each Model We Got the Best Model Gradient Boosting Regressor,Because it has the Higher R-square value.

The Gradient Boosting Regressor has a higher R-squared value,it explains more variance in the target variable, that is, car prices. The higher the R-squared value, the better the model fits in describing the relationship of the independent features with the dependent variable
it has the lowest MSE among all the models. The lower MSE means that the model's predictions are closer to the true values, meaning fewer errors in predicting the car prices.
The MAE for this model is also the lowest, showing that on average, its predictions are better than those of other models. Lower MAE shows fewer average errors in prediction.
##  Feature Importance Analysis
It is essential to Find the Feature that affect the Car Price here we use SelectKBest to find the features.the important features that Affect the car price are:- 
carwidth,curbweight,enginesize,horsepower,highwaympg
