1. What is the definition of a target function? In the sense of a real-life example, express the target
function. How is a target function&#39;s fitness assessed?

2. What are predictive models, and how do they work? What are descriptive types, and how do you
use them? Examples of both types of models should be provided. Distinguish between these two
forms of models.

3. Describe the method of assessing a classification model&#39;s efficiency in detail. Describe the various
measurement parameters.

4.
i. In the sense of machine learning models, what is underfitting? What is the most common
reason for underfitting?

ii. What does it mean to overfit? When is it going to happen?

iii. In the sense of model fitting, explain the bias-variance trade-off.


5. Is it possible to boost the efficiency of a learning model? If so, please clarify how.

6. How would you rate an unsupervised learning model&#39;s success? What are the most common
success indicators for an unsupervised learning model?

7. Is it possible to use a classification model for numerical data or a regression model for categorical
data with a classification model? Explain your answer.

8. Describe the predictive modeling method for numerical values. What distinguishes it from
categorical predictive modeling?

9. The following data were collected when using a classification model to predict the malignancy of a
group of patients&#39; tumors:

i. Accurate estimates – 15 cancerous, 75 benign
ii. Wrong predictions – 3 cancerous, 7 benign
Determine the model&#39;s error rate, Kappa value, sensitivity, precision, and F-measure.

10. Make quick notes on:

i) The process of holding out

ii) Cross-validation by tenfold

iii) Adjusting the parameters

11. Define the following terms:

i) Purity vs. Silhouette width

ii) Boosting vs. Bagging

iii) The eager learner vs. the lazy learner

# Answers


1) The target function in machine learning represents the ideal relationship or mapping between input features and output labels that a model aims to learn from the training data.
Real-Life Example: In a spam email classification task, the target function would map email content (features) to two labels: "spam" or "not spam."
Assessment: The fitness of a target function is assessed by comparing the predictions made by the model trained on this function to the actual outcomes in the training dataset. Metrics like accuracy, loss, or other evaluation criteria are used.
Predictive Models vs. Descriptive Models:

2) Predictive Models: These aim to make predictions or forecasts based on input data. Examples include linear regression, decision trees, and neural networks. They use historical data to predict future outcomes.
Descriptive Models: These aim to describe patterns or relationships in data without making predictions. Examples include clustering algorithms like K-means, which group data points based on similarity.

3) Classification Model Assessment:

Metrics: Common metrics for assessing classification model efficiency include accuracy, precision, recall (sensitivity), F1-score, ROC curve, and AUC-ROC. Confusion matrix is often used to compute these metrics.
Parameters: These metrics are computed based on the number of true positives, true negatives, false positives, and false negatives.
Underfitting, Overfitting, and Bias-Variance Trade-off:

4)
i. Underfitting: Occurs when a model is too simple to capture the underlying patterns in the data. It often results from inadequate model complexity.
ii. Overfitting: Occurs when a model is too complex and fits the training data noise, resulting in poor generalization to new data.
iii. Bias-Variance Trade-off: Finding the right balance between model bias (underfitting) and variance (overfitting). It involves adjusting the model's complexity to achieve good generalization.
Improving Model Efficiency:

5) Yes, model efficiency can be boosted:
By selecting more relevant features.
Tuning hyperparameters.
Increasing the amount of training data.
Using ensemble techniques.
Regularizing the model.

6) Unsupervised Learning Model Success:

Success is often indicated by how well the model uncovers hidden patterns or structures in unlabeled data.
Common indicators include clustering quality (e.g., silhouette score), visualization of clusters, or reduced dimensionality.


7) Using Classification and Regression Models:

Generally, classification models are used for categorical data (e.g., classifying emails as spam or not).
Regression models are used for numerical data (e.g., predicting house prices based on features).
They are not interchangeable as their output types (categorical vs. numerical) and modeling objectives differ.


8) Predictive Modeling for Numerical vs. Categorical Values:

Numerical predictive modeling aims to predict a continuous numeric target variable.
Categorical predictive modeling aims to predict categories or classes.

9) Classification Model Evaluation:

Error Rate = (Wrong Predictions / Total Predictions) = (3 + 7) / (15 + 75) = 0.1
Kappa Value, Sensitivity, Precision, and F-measure require the confusion matrix to compute, and the values depend on the specific values in the matrix.
Quick Notes:

10)
i) Holding Out: A method to split data into training and testing sets, keeping a portion for testing.
ii) Cross-Validation by Tenfold: A technique to assess model performance by splitting data into 10 equal parts, using 9 for training and 1 for testing iteratively.
iii) Adjusting Parameters: Fine-tuning hyperparameters of a model to optimize its performance.

11)
i) Purity vs. Silhouette Width: Purity measures how well-defined clusters are in a clustering task, while Silhouette Width quantifies the separation between clusters.
ii) Boosting vs. Bagging: Boosting is an ensemble method that combines weak learners sequentially to create a strong learner, while Bagging combines multiple independent learners to reduce variance.
iii) Eager Learner vs. Lazy Learner: Eager learners build a model during training and make predictions quickly (e.g., decision trees). Lazy learners delay building a model until prediction time (e.g., k-nearest neighbors).
