1. What are the key tasks involved in getting ready to work with machine learning modeling?

2. What are the different forms of data used in machine learning? Give a specific example for each of
them.

3. Distinguish:

i). Numeric vs. categorical attributes

ii). Feature selection vs. dimensionality reduction

4. Make quick notes on any two of the following:

i) The histogram

ii) Use a scatter plot  

iii) PCA (Personal Computer Aid)

5. Why is it necessary to investigate data? Is there a discrepancy in how qualitative and quantitative data are explored?

6. What are the various histogram shapes? What exactly are ‘bins&#39;?

7. How do we deal with data outliers?

8. What are the various central inclination measures? Why does mean vary too much from median in certain data sets?

9. Describe how a scatter plot can be used to investigate bivariate relationships. Is it possible to find outliers using a scatter plot?

10. Describe how cross-tabs can be used to figure out how two variables are related.

# Answers

#1 Data Collection: Gather relevant data that is suitable for your machine learning task.

Data Cleaning: Clean and preprocess the data by handling missing values, outliers, and formatting issues.

Feature Engineering: Create new features or transform existing ones to improve model performance.

Data Splitting: Divide the dataset into training, validation, and test sets.

Model Selection: Choose an appropriate machine learning algorithm or model.

Model Training: Train the selected model on the training data.

Model Evaluation: Evaluate the model's performance on the validation set and fine-tune as needed.

Hyperparameter Tuning: Optimize the model's hyperparameters to achieve the best performance.

Final Model Testing: Assess the model's performance on the test set to ensure generalization.

Deployment: Deploy the trained model in a production environment if applicable.

#2 Numeric Data: This includes numerical values such as integers or floating-point numbers. Example: Temperature readings (e.g., 25.5°C).

Categorical Data: Categorical data represents discrete categories or labels. Example: Types of fruits (e.g., "apple," "banana," "orange").

Text Data: Textual data includes strings of text, such as product reviews, articles, or tweets.

Image Data: Image data consists of pixel values in an image. Example: Photographs, medical scans.

Time Series Data: Time series data is collected at regular time intervals. Example: Stock prices over time.

#3 i)

Numeric Attributes: These are continuous or discrete numerical values. They can be used for mathematical operations and measurements.

Categorical Attributes: These represent discrete categories or labels. They are typically used for classification tasks and cannot be directly used for mathematical operations.

ii) Feature Selection: It involves choosing a subset of the most relevant features from the original dataset. It aims to improve model performance and reduce complexity.

Dimensionality Reduction: It reduces the number of features while preserving as much information as possible. Techniques like Principal Component Analysis (PCA) are used for this purpose.

#4 i) A histogram is a graphical representation of the distribution of data. It displays the frequency or count of data points in different intervals or "bins" along a continuous range.
Histograms help visualize the data's central tendency, spread, and shape of the distribution.

ii) A scatter plot is used to investigate the relationship between two numeric variables. Each data point is represented as a point on the plot, with one variable on the x-axis and the other on the y-axis.
Outliers can be visually identified as data points that deviate significantly from the general pattern of the scatter plot.

iii) PCA is a dimensionality reduction technique used to reduce the number of features in a dataset while retaining most of the information.
It's not a personal computer aid but a mathematical technique for data analysis.

#5 Investigating data is crucial to understand its characteristics, identify outliers, and determine the most appropriate preprocessing steps and modeling techniques.
Qualitative data (categorical) and quantitative data (numeric) may require different exploration methods, but the goal is to gain insights into the data's properties and potential challenges.

#6 Histogram shapes can include "normal" (bell-shaped), "skewed" (positively or negatively), "bimodal" (two peaks), and others.
"Bins" in a histogram are intervals or ranges used to group data points. They determine the width of the bars in the histogram and affect its granularity.

#7 Outliers can be handled by removing them if they are erroneous or extreme, or by transforming them (e.g., winsorization) to reduce their impact on the analysis.
Care should be taken to ensure that outlier treatment is appropriate for the specific context and doesn't distort the data.

#8 Measures of central tendency include the mean (average), median (middle value), and mode (most frequent value).
Mean can vary significantly from the median in datasets with outliers or skewed distributions because it is sensitive to extreme values.

#9 A scatter plot helps visualize how two numeric variables relate to each other.
Outliers can be identified as data points that fall far from the general trend in the scatter plot.

#10 Cross-tabs are used to analyze the relationship between two categorical variables.
They display the frequency or count of data points that fall into different combinations of categories for the two variables, making it easier to identify patterns and associations.


```python

```
