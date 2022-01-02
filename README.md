# Wine-Quality-EDA-Prediction-ML

Data Set Information:

The dataset was downloaded from the UCI Machine Learning Repository.

These datasets can be viewed as classification or regression tasks(I accounted as Regression). The classes are ordered and not balanced (e.g. there are munch more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

Two datasets were combined and few values were randomly removed.

Attribute Information:

Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol

Output variable (based on sensory data):
12 - quality (score between 0 and 10)

In the notebook I first filtered out the dataset, then worked on different ML models and Finally finded out the best one.
