1. What are the key tasks involved in getting ready to work with machine learning modeling?
2. What are the different forms of data used in machine learning? Give a specific example for each of
them.
3. Distinguish:

i) Numeric vs. categorical attributes

ii) Feature selection vs. dimensionality reduction

4. Make quick notes on any two of the following:

i) The histogram

ii) Use a scatter plot

iii) PCA (Personal Computer Aid)

5. Why is it necessary to investigate data? Is there a discrepancy in how qualitative and quantitative
data are explored?

6. What are the various histogram shapes? What exactly are ‘bins&#39;?

7. How do we deal with data outliers?

8. What are the various central inclination measures? Why does mean vary too much from median in
certain data sets?

9. Describe how a scatter plot can be used to investigate bivariate relationships. Is it possible to find
outliers using a scatter plot?

10. Describe how cross-tabs can be used to figure out how two variables are related.

# Answers

#1 What are the key tasks involved in getting ready to work with machine learning modeling?

To work with machine learning modeling the key tasks involved are:

Data Ingestion --> Data cleaning --> Feature engineering and feature selection --> Model Training --> Model Validation --> Monitoring

#2 What are the different forms of data used in machine learning? Give a specific example for each of them.

Different forms of data used are categorical and numerical data. Eg-> Age of house is a numerical whereas the type of house like villa or bunglow is a categorical data 

3 i) Numerical data are integer or float type data that can be fed to our model without any type of encoding whereas categorical data are those which must be manipulated using an encoding technique for our model to understand.

ii) Feature selection refers to selection of input fields that is to be fed to the model for proper working for our model whereas in dimensionality reduction, the no. of input fields are reduced to reduce the complexity of our model. 

4 i) Histogram is used to summarize discrete or continuous data that are measured on an interval scale.


```python
# ii) We can use scatter plot in following way:

import matplotlib.pyplot as plt

x = [1,2,3,4,5,6,7,8,9]
y = [1,4,9,16,25,36,49,64,81]

plt.scatter(x, y)
plt.show()
```


    
![png](output_7_0.png)
    


iii) PCA (Personal Computer Aid) is reduction of dimensionality of the data to smaller dimension which represents say 80-90% of data but also reducing the complexity of our model

#5 Why is it necessary to investigate data? Is there a discrepancy in how qualitative and quantitative data are explored?

Yes, it's important to investigate the data as that will be the foundation for our model. Our model will be trained on the data we will be feeding it. The qualitatuve and quantative data referred to as catgeorical and numerical data are explored differently in terms of feature engineering, removing outliers etc.

#6 What are the various histogram shapes? What exactly are ‘bins'?

Various shapes of histograms could be symmetric, skewed, bimodal and uneven shapes. Bins are intervals over which a particular data exists. The height of the histogram over that bin represents the frequency of data points belonging to that particular interval.

#7 How do we deal with data outliers?

For outliers we remove the the data points not belonging upto 3 standard deviations from the mean data.

#8 What are the various central inclination measures? Why does mean vary too much from median in certain data sets?

Mean, median and mode are the various central inclination measures. Due to presence of outliers the mean vary too much from median in certain data sets.

#9 Describe how a scatter plot can be used to investigate bivariate relationships. Is it possible to find outliers using a scatter plot?

A large amount of scatter around the line indicates a weak relationship. Little scatter represents a strong relationship. If all points fall directly on a straight line, we have a perfect linear relationship between our two variables. 

To identify outliers in a scatter plot, you can visually inspect the graph for data points that are very far from the main cluster or trend.


#10 Describe how cross-tabs can be used to figure out how two variables are related.

Cross tabulations — also referred to as contingency tables or crosstabs — group variables together and enable researchers to understand the correlation between the different variables.


```python

```
