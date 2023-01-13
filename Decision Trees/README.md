This personal project investigates Supervised Learning techniques such as Decision Trees.

This folder contains 3 files:

Titanic.csv:
* Dataset used for these programs. Obtained from: https://www.kaggle.com/competitions/titanic/data?select=train.csv

DecisionTree1:
* This program creates a Decision Tree that can predict the survival of passengers on the Titanic.
* The data is first cleaned, then split into the Training, Development and Test sets.
* Model is trained and the accuracy of the model is calculated.
* The effects of the 'maxdepth' parameter on the models accuracy is observed.
* The optimum value for 'maxdepth' is obtained and used to train the final model.

DecisionTree2:
* This program creates a Bagged, Random Forest & Boosted Tree model for the titanic dataset.
* The Random Forest model is then used to determine which features contribute the most to predicting whether a passenger survives or not.
* 1 out of the 3 models are selected, and the effects of varying the 'n_estimators' and 'max_depth' parameters is observed.
* The accuracy of the models are calculated as well as the optimal 'n_estimators' and 'maxdepth' values.
