# titanic_predictions
Testing different machine learning models for predicting passenger deaths on the Titanic.

The dataset for this project came from the [Titanic Challenge on Kaggle](https://www.kaggle.com/competitions/titanic).

The three types of models I used, all of which were imported from `sklearn`, were:
1. A kernel-based support vector model (SVC)
2. A neural network model (MLPClassifier)
3. A decision tree model (DecisionTreeClassifier)

Using these three models, I experimented with the following to try to achieve the best possible results:
- Preprocessing the data with standard normalization and PCA normalization
- Tuning hyperparameters of the model
- Adding/removing features used for training

A more detailed explanation of my process can be found in the writeup document `Writeup.pdf`.
