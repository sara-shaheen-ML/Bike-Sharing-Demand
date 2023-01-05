# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### NAME HERE

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: Add your explanation

### What was the top ranked model that performed?
TODO: Add your explanation

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Add your explanation
I Created a histogram of all features to show the distribution of each one relative to the data. This is part of the exploritory data analysis

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|?|?|?|?|
|add_features|?|?|?|?|
|hpo|?|?|?|?|

|    | model              | hpo1                                                                                                                                                              | hpo2                                                                   | hpo3                                                                                                |   score |
|---:|:-------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------|--------:|
|  0 | initial_model      | default values                                                                                                                                                    | default values                                                         | default values                                                                                      | 1.81144 |
|  1 | add_features_model | default values                                                                                                                                                    | default values                                                         | default values                                                                                      | 0.68613 |
|  2 | hpo_model          | XGB: Estimators[lower=100, upper=500, default=100], max_depth[ ag.space.Int(lower=6, upper=10, default=6], eta (LEARNING RATE): [lower=0.01, upper=0.3, log=True] | GBM: num_boost_round [100], num_leaves[lower=26, upper=66, default=36] | CAT: Iterations[100], learning_rate[lower=0.01, upper=0.3, log=True] , depth [lower=0.01 upper=0.3] | 0.48182 |

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
