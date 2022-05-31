# Feature-Selection
Feature selection - Correlation and P-Value


FEATURE SELECTION - CORRELATION AND P-VALUE



Often when we get a dataset, we might find a plethora of features in the dataset. All of the features we find in the dataset might not be useful in building a machine learning model to make the necessary prediction. Using some of the features might even make the predictions worse. So, feature selection plays a huge role in building a machine learning model.



In this article we will explore two measures that we can use on the data to select the right features.



What is correlation?

Correlation is a statistical term which in common usage refers to how close two variables are to having a linear relationship with each other.

For example, two variables which are linearly dependent (say, x and y which depend on each other as x = 2y) will have a higher correlation than two variables which are non-linearly dependent (say, u and v which depend on each other as u = v2)

How does correlation help in feature selection?



Features with high correlation are more linearly dependent and hence have almost the same effect on the dependent variable. So, when two features have high correlation, we can drop one of the two features.





P-value

Before we try to understand about about p-value, we need to know about the null hypothesis.

Null hypothesis is a general statement that there is no relationship between two measured phenomena.





What is p-value?

Note: p-value is not an ideal metric for feature selection and here is why;



P-value or probability value or asymptotic significance is a probability value for a given statistical model that, if the null hypothesis is true, a set of statistical observations more commonly known as the statistical summary is greater than or equal in magnitude to the observed results.





In other words, P-value gives us the probability of finding an observation under an assumption that a particular hypothesis is true. This probability is used to accept or reject that hypothesis.

How does p-value help in feature selection?

Removal of different features from the dataset will have different effects on the p-value for the dataset. We can remove different features and measure the p-value in each case. These measured p-values can be used to decide whether to keep a feature or not.



For an application of this article, you can visit the GitHub link below to get access to my notebook which gives a clear and concise illustration.
