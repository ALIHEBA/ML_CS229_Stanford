# ML_CS229_Stanford
# 1. Linear regression 
is a supervised learining algorithm used when target / dependent variable continues real number. It establishes relationship between dependent variable  y  and one or more independent variable  x  using best fit line.
 It work on the principle of ordinary least square  (OLS)  / Mean square errror  (MSE) . In statistics ols is method to estimated unkown parameter of linear regression function
 it's goal is to minimize sum of square difference between observed dependent variable in the given data set and those predicted by linear regression fuction.
 The goal of supervised learning is to learn a hypothesis function  h , for a given training set that can used to estimate  y  based on  x . So hypothesis fuction represented as
![image](https://user-images.githubusercontent.com/43907156/164890656-f473a40b-f0c4-4830-a969-a214b0b81ed8.png)
A cost function measures how much error in the model is in terms of ability to estimate the relationship between  x  and  y . We can measure the accuracy of our hypothesis function by using a cost function. This takes an average difference of observed dependent variable in the given the dataset and those predicted by the hypothesis function.
![image](https://user-images.githubusercontent.com/43907156/164891030-09b94e5d-2d33-433d-bacf-85c006255afe.png)

# Heatmap
According to the Oxford dictionary, a heatmap (or heat map) is “a representation of data in the form of a map or diagram in which data values are represented as colors”. One of the most effective ways to express a heatmap that can be used on mathematical models is through the use of matrices where each cell represents a square portion of space in a given measuring distance system and the colors represent the intensity of the studied event that happened on each cell mapped.

# Encoding
Machine learning algorithms cannot work with categorical data directly, categorical data must be converted to number.

Label Encoding
One hot encoding
Dummy variable trap

# Label encoding
refers to transforming the word labels into numerical form so that the algorithms can understand how to operate on them.

# A One hot encoding
is a representation of categorical variable as binary vectors.It allows the representation of categorical data to be more expresive. This first requires that the categorical values be mapped to integer values, that is label encoding. Then, each integer value is represented as a binary vector that is all zero values except the index of the integer, which is marked with a 1.

# The Dummy variable trap
is a scenario in which the independent variable are multicollinear, a scenario in which two or more variables are highly correlated in simple term one variable can be predicted from the others.

# A Box Cox transformation
is a way to transform non-normal dependent variables into a normal shape. Normality is an important assumption for many statistical techniques; if your data isn’t normal, applying a Box-Cox means that you are able to run a broader number of tests. All that we need to perform this transformation is to find lambda value and apply the rule shown below to your variable.

![image](https://user-images.githubusercontent.com/43907156/164893232-b75f019a-011b-492f-823b-34dd940a65d4.png)


![image](https://user-images.githubusercontent.com/43907156/164893448-49813e9c-682b-4542-8524-68fab6c579e7.png)



