1. What is the estimated depth of a Decision Tree trained (unrestricted) on a one million instance
training set?

2. Is the Gini impurity of a node usually lower or higher than that of its parent? Is it always
lower/greater, or is it usually lower/greater?

3. Explain if its a good idea to reduce max depth if a Decision Tree is overfitting the training set?

4. Explain if its a good idea to try scaling the input features if a Decision Tree underfits the training
set?

5. How much time will it take to train another Decision Tree on a training set of 10 million instances
if it takes an hour to train a Decision Tree on a training set with 1 million instances?

6. Will setting presort=True speed up training if your training set has 100,000 instances?

7. Follow these steps to train and fine-tune a Decision Tree for the moons dataset:

a. To build a moons dataset, use make moons(n samples=10000, noise=0.4).

b. Divide the dataset into a training and a test collection with train test split().

c. To find good hyperparameters values for a DecisionTreeClassifier, use grid search with cross-
validation (with the GridSearchCV class). Try different values for max leaf nodes.

d. Use these hyperparameters to train the model on the entire training set, and then assess its
output on the test set. You can achieve an accuracy of 85 to 87 percent.

8. Follow these steps to grow a forest:

a. Using the same method as before, create 1,000 subsets of the training set, each containing
100 instances chosen at random. You can do this with Scikit-ShuffleSplit Learn&#39;s class.

b. Using the best hyperparameter values found in the previous exercise, train one Decision
Tree on each subset. On the test collection, evaluate these 1,000 Decision Trees. These Decision

Trees would likely perform worse than the first Decision Tree, achieving only around 80% accuracy,
since they were trained on smaller sets.

c. Now the magic begins. Create 1,000 Decision Tree predictions for each test set case, and
keep only the most common prediction (you can do this with SciPy&#39;s mode() function). Over the test
collection, this method gives you majority-vote predictions.

d. On the test range, evaluate these predictions: you should achieve a slightly higher accuracy
than the first model (approx 0.5 to 1.5 percent higher). You&#39;ve successfully learned a Random Forest
classifier!

# Answers

1. The estimated depth of a Decision Tree trained on a one million instance training set can vary widely depending on the complexity of the data and the features. In an unrestricted tree (no maximum depth set), it is possible for the tree to become very deep, potentially reaching depths in the hundreds or even more. However, it's essential to note that extremely deep trees may lead to overfitting and may not generalize well to unseen data.

2. The Gini impurity of a node is usually lower than that of its parent. The primary goal of splitting nodes in a Decision Tree is to reduce impurity, so the Gini impurity at child nodes is typically lower than at their parent. This reduction in impurity ensures that the tree is making decisions that separate the classes more effectively, resulting in better discrimination between classes.

3. Yes, it is generally a good idea to reduce the maximum depth of a Decision Tree if it is overfitting the training set. Overfitting occurs when the tree becomes too deep and captures noise in the data, making it perform poorly on unseen data. By limiting the depth of the tree (e.g., by setting the max depth hyperparameter), you can reduce its complexity, increase its generalization ability, and mitigate overfitting.

4. No, scaling the input features is generally not necessary to address underfitting in a Decision Tree. Decision Trees are not sensitive to the scale of input features because they make binary decisions based on feature values. Underfitting is more likely to be related to other factors such as insufficient tree depth, lack of feature importance, or not using an appropriate decision tree algorithm or hyperparameters.

5. Training time for Decision Trees typically scales with the number of instances and the complexity of the data. If it takes an hour to train a Decision Tree on a training set with 1 million instances, training a Decision Tree on a training set with 10 million instances may take significantly longer. The exact time would depend on various factors, including hardware, software optimization, and the specific dataset.

6. Setting presort=True can potentially speed up training for Decision Trees, but it's generally recommended for smaller datasets. When you have a training set with 100,000 instances, using presorting may not provide a significant speedup and could even slow down training. The presorting process involves sorting the data for each node, which can be computationally expensive. For larger datasets, the overhead of presorting can outweigh any potential benefits, so it's often better to leave presort as the default (False) for larger datasets.


```python

```
