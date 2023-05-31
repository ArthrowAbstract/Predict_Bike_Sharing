# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Devanshu Sinha

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
When I tried to submit my predictions, I realized that the output of the predictor was a list of probabilities for each class. However, the Kaggle competition required that I submit a single number for each prediction. 

### What was the top ranked model that performed?
The top ranked model was obtained when more features were added.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
The exploratory analysis found that the following features were most correlated with the target variable temp, atemp, humidity, windspeed, weekday.

### How much better did your model preform after adding additional features and why do you think that is?
My model performed significantly better after adding additional features. The score on the Kaggle leaderboard increased from 1.8 to 1.3. I think that the additional features helped the model to learn more complex relationships between the features and the target variable.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
My model performed very slightly better after trying different hyper parameters. The score on the Kaggle leaderboard didn't change much. I think that there was no improvement  due to the fact that I was not able to find a set of hyper parameters that were more suited to my dataset.

### If you were given more time with this dataset, where do you think you would spend more time?
With a large dataset, more time could be spend on feature engineering as it's a time-consuming process. So, understanding features can ease the complex process of feature engineering.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.


### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
