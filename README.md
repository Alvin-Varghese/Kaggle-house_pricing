# Kaggle's Housing Price Prediction

This is a beginner's revised attempt at improving the score (and ranking) for the Kaggle. Check out the competition [here](https://www.kaggle.com/c/home-data-for-ml-course).
This a jupyter notebook implementation and the commands for installing libraries are for an Anaconda-based installation.

My earlier stats were:
| Score | Rank | Method |
| ------ | ------ | ----|
| 21248.846 | 21113 | RandomForest |
| 16619.076 | 13117 | RandomForest with tuned hyperparameters |
| 12283.609 | 211 | (Various) Ensemble models|

The objective of the competition was, on it's page,  
> It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

The evaluation criterion was the Root Mean Squared Error(RMSE).


### Prerequisites

  - **train.csv** for training and validating the models 
  - **test.csv** for testing and submitting the solutions
  - [Optional]**sample_submission.csv** for writing the output


#### Installation of required libraries

Apart from the usual scikit-learn library, this implementation also requires [MLXtend](http://rasbt.github.io/mlxtend/),  [XGBoost](https://xgboost.readthedocs.io/en/latest/) and [LightGBM](https://lightgbm.readthedocs.io/en/latest/) to run.

Install the dependencies through the terminal.

```sh
$ conda install mlxtend
$ conda install -c conda-forge xgboost
$ conda install -c conda-forge lightgbm
```

You can run the notebook now and while I have tried to add comments wherever possible and kept the code in segments for esier understanding, I'll be updating this ReadMe or the notebook itself for more explanations.

License
------
Apache 2.0 