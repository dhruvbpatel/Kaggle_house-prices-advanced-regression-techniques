# house-prices-advanced-regression-techniques
 - This is my submission for Kaggle's house-prices-advanced-regression-techniques Competition
 - you can find the link to the competition [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
 - With the solution was i able to secure a position in top 11% in the leaderboard.
---

 - **Aim**:  The aim of this competition is to predict the SalePrice of the House given the dataset with over more than 80 parameters.

 - Approach:

	1. Used various preprocessing techniques to prepare the training data
	2. split dataset into train and validation using train_test_split method
	3. created pipelines to impute , scale and OneHotEncode the categorical /numerical columns respectively
	4. Initialized XGBoostRegressor, RandomForest and ElasticNet models.
	5. using GridSearch cross validation tried to find the best parameters for the models
	6. finally fit the model train data and predicted the result using validation dataset
	7. Here Mean Squared Error metric is used for calculating the score of the model.
	8. Finally , predict the output using test data and submit solution on kaggle.


---
I hope you have liked this project , if you have any doubts/queries feel free to ping me on
 -	linkedIn :https://www.linkedin.com/in/dhruv-patel-1057
 -	twitter: https://www.twitter.com/dhruvhimself
 
 Also if you would like to contribute to this you are most welcome, feel free to open up a pull request ✌.
 
 

	 
