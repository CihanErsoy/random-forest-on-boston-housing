# random-forest-on-boston-housing
Random forest regression model is implemented on boston housing dataset.  Hyperparameter tuning is used. 

This has been prepared as a term project for Machine Learning Course related to my master degree. I sought answers for questions below:
How does optimization affect a random forest model? Does optimization increase the accuracy? How do different optimization models affect the accuracy score of a random forest model?

Dataset is called from sklearn dataset library. Basic visualization and data exploration implemented first, then model was built. 

MEDV feature (Median value of owner-occupied homes in $1000's) is our target variable. Then rest of the features are used as predictors. 
Data is not subject to cleansing as it already doesn't have any missing values. 

Accuracy is found as 0.876, then we implement optimization, accuracy score increases to 0.891. Optimization shows us that increasing the number of trees helps us to increase the accuracy score till our model reaches the optimization. Even though we try options like 500 trees, 800 trees during the tuning, optimization algorithm showes us 100 trees are most optimized number for our random forest in this particular case.
