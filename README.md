# ML | Predicting car prices using linear regression and DecisionTreeRegressor

<p align="center">
  <img src="images_to_report\car.jpg" width="400">
</p>


In this project, I implemented car price prediction using linear regression with regularization (ridge regression) and the DecisionTreeRegressor algorithm.

Link to the data used in the project from the kaggle website: https://www.kaggle.com/datasets/CooperUnion/cardataset

Remark: comments in the code will be written in Russian

## IDA, feature transformation and ML model development
[main](main.ipynb) - The main code of the program is presented in this notebook. I performed exploratory analysis of the data, encoded the features of the object type and used two different models for prediction, a tree model - DecisionTreeRegressor and a linear regression model with regularization - Ridge from the sklearn library.

## Result
The trained models were tested on a dedicated test dataset and showed the following MAPE metric values:
- Ridge - 35%
- DecisionTreeRegressor - 8%

As we can see, the tree model showed the best result even though the hyperparameters were not selected separately. It is possible to improve the quality of the model by selecting hyperparameters.
