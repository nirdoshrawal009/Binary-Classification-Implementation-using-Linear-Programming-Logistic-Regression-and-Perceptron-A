# Binary-Classification-Implementation-using-Linear-Programming-Logistic-Regression-and-Perceptron-A
Choose an appropriate dataset of your choice such that every record (example) has at least 5 features which are numeric in nature and there is at least one attribute (feature) which is binary in nature. You can use the binary attribute as the binary target label to be predicted. In case you want to use a target variable which has more than two distinct values, then you can map them into two sets and give label 1 to one of the sets and 0 to the other. Thus, a multiclass classification task can be reduced to binary classification task.
Split your dataset into a training set and a test set. You can try different splits: 70:30 (70% training, 30% testing), 80:20 or 90:10 split.
On the training set, train the following classifiers:
1. Half-Space classifier implemented using LP solver (one such solver is scipy.optimize.linprog)
2. Half-Space classifier implemented using Perceptron Algorithm (implement the iterations)
3. Logistic Regression Classifier
