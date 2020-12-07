# Predict the Survival of Titanic Passenger

We create a machine learning model to predict the survival status of a Titanic Passenger using Random Forest.

## Dataset

Training and Testing Dataset that we were uses are sourced from kaggle datasets : https://www.kaggle.com/c/titanic 

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.
The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.


## Model

For this model, we use Random Forest, and only using several features such as 
* “Pclass”
* “Sex”
* “SibSp”
* “Parch”
* “Age”
* “Fare”
* “Embarked”

## Prerequisites

There is no need to install anything because it is basically written in kaggle notebook with cloud service.

* Copy this repository link to your google colab https://github.com/fadelnast/ML-Learning-Titanic/blob/master/Getting_started_with_Titaninc_dataset.ipynb 
* After successfully open the notebook, you can get the datasets in here https://www.kaggle.com/c/titanic 


## Built with
SKLearn



