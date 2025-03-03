KNN (K-Nearest Neighbors) is a supervised machine learning classification algorithm. It is a Lazy Evaluator & can be applied when the target variable is categorical. Here, the target variable is profile income and we need to make predictions for it. K resembles the no. of neighbors and is a hyperparameter. In this project, I have used a technique of tradeoff between accuracy & stability to determine the best value of k and thereby got the best model built using Euclidean distance principle on Adult Income dataset.

Alternatively, I have also used GridSearchCV() to check for the best hyperparameters particularly for the value of k.  
In this case, the former tradeoff technique works really well in comparison to the latter technique.

Following basic steps are executed as usual:

1. Understand the problem statement/requirement.
2. Import the necessary libraries.
3. Load the dataset.
4. Data pre-processing.
5. Random Sampling with train test split.
6. Build the model on train data.
7. Use Tradeoff/GridSearch to perform the best hyperparameter tuning.
8. Test the model on test data.
9. Build the confusion matrix and evaluate using various evaluation parameters.
10. Re-run the model from some previous steps if required.
