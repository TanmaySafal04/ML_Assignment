1. What does one mean by the term &quot;machine learning&quot;?

2.Can you think of 4 distinct types of issues where it shines?

3.What is a labeled training set, and how does it work?

4.What are the two most important tasks that are supervised?

5.Can you think of four examples of unsupervised tasks?

6.State the machine learning model that would be best to make a robot walk through various
unfamiliar terrains?

7.Which algorithm will you use to divide your customers into different groups?

8.Will you consider the problem of spam detection to be a supervised or unsupervised learning
problem?

9.What is the concept of an online learning system?

10.What is out-of-core learning, and how does it differ from core learning?

11.What kind of learning algorithm makes predictions using a similarity measure?

12.What&#39;s the difference between a model parameter and a hyperparameter in a learning
algorithm?

13.What are the criteria that model-based learning algorithms look for? What is the most popular
method they use to achieve success? What method do they use to make predictions?

14.Can you name four of the most important Machine Learning challenges?

15.What happens if the model performs well on the training data but fails to generalize the results
to new situations? Can you think of three different options?

16.What exactly is a test set, and why would you need one?

17.What is a validation set&#39;s purpose?

18.What precisely is the train-dev kit, when will you need it, how do you put it to use?

19.What could go wrong if you use the test set to tune hyperparameters?

# Answers

#1 Machine Learning is like giving the machines, the ability to think and respond just like we humans do. Just like we make decisions based on our experience, similarly the machines are trained with data and they respond similarly the way in which they are expected to behave.

#2 Four distinct types of issues where ML shines:
    i) Grouping(clustering)
    ii) Prediction of diseases in medical field
    iii) Weather forecasting
    iv) Prediction of stock market prices

#3 Labelled training set is one in which the target which is to be predicted is known. We train our model using this data with the input and output features and then use test data further to predict the outcome.

#4 Classification and Regression are the 2 most important tasks that are supervised.

#5 Four examples of unsupervised task: 
     i) Creating groups of people who like different sports
     ii) Reducing the input features(PCA)
     iii) Grouping people based on their streams
     iv) Predicting what will one buy based on what they actually buy(similarity)

#6 Models developed through reinforcement learning would be best suitbale model that would be best to make a robot walk through various unfamiliar terrains

#7 K-Means would be the best algorithm to divide people into different groups.

#8 Spam detection will be considered as a unsupervised learning problem

#9 An Online learning system is on where the training of our model happens not in our our local machine but on a cloud system where data is fed sequentially as the data is available to make our model perform better in future.

#10 Out of core learning is basically when the training data can't be available on our system as it's high volume data hence this data is usally available in a data storage or a web repository. 

#11  KNN is a learning algorithm makes predictions using a similarity measure

#12 Model parameters are those that are obtained only after the training of our model whereas hyperparameters are those which are used to fine tune our model to give better results. 

#13 Model based training algorithms search for optimal values for the model's parameters, often called theta. This searching, or "learning", is what machine learning is all about. Model-based system learn by minimizing a cost function that measures how bad the system is at making predicitons on new data, plus a penalty for model complexity if the model is regularized.

#14 Four challenges in Machine Learning:
     i) Unbalanced dataset
     ii) NOisy data
     iii) Missing and null values
     iv) overfitting and underfitting

#15 The situation is called Overfitting. In such case we usually: 
      i) Cross-validation and hyperparameters tuning 
      ii) Reducing the outliers and multicollinearity
      iii) Assigning weights to data that is less in target variable

#16 Test set is used to monitor and check the performance of our model.

#17 Validation set's puropse is to check the performance of the model and perfrom necessary tuning if required.

#18 Training process emits the parameters of a model and hence the sole purpose of training data is to make a decision about which parameters to pick given huge options to choose from.

The goal of dev-set is to rank the models in term of their accuracy and helps us decide which model to proceed further with.

We use test-set as a proxy for unseen data and evaluate our model on test-set.

#19 If we use test set to perform hyperparameters the our model won't perform well as the test data is usually less hence it won't give a proper representation of the meaning of our actual data and also it would lead to overfitting.
