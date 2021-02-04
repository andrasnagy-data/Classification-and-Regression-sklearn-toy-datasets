**Data Science Projects based on sklearn's toy datasets**

In this repository, I created classification and regression models, however I did not do any feature selection and engineering (which is in my opinion the bulk of the Data Science workflow). 
I used sklearn's GridSearchCV and cross_val_score objects to achive the highest accuracy for the different models. In the case of the Boston housing price prediction project, I used the cross-validated mean accuracy to compare two different models, as to choose the better performing model.

- The Iris species classifier's mean cross-validated accuracy is ~98.7%.
- The digits classifier's mean cross-validated accuracy is ~97.8%.
- The ridge regression model on avarage is off by ~3800 USD (this is ~8% of the range of target) when predicting the prices of given houses in Boston.
