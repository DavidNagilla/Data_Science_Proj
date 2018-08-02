# Data_Science_Proj

This paper presents a study of predicting the attendance of Twitter
users at the FIFA 2014 World cup event based on geotagged and
non-geotagged posts. We propose a machine learning approach
for analysing social media posts of users discussing the event to
predict their attendance.

# Data 

Data Source :  http://blog.aylien.com/text-analytics-meets-2014-world-cup-tweets-part-1/.

# Models

Logistic regression (Predictive Learning Model):. Its mainlx implemented because it performs binary classification, so the
label outputs which are binary, similar to our study where we have two
classes - attending and not attending. It is known to be fast and
simple for execution.

Naive Bayes Classifier (Generative Learning Model): It is a clas-
sification technique based on Bayes’ Theorem with an assumption
of independence among predictors. In simple terms, a Naive Bayes
classifier assumes that the presence of a particular feature in a class
is unrelated to the presence of any other feature.

Decision tree: Decision tree builds classification or regression
models in the form of a tree structure. It breaks down a data set into
smaller and smaller subsets while at the same time an associated
decision tree is incrementally developed. The result is a tree with
decision nodes and leaf nodes. Each node represents a single input
variable (x) and is split point on that variable. The leaf nodes of
the tree contain an output variable (y) which is used to make a
prediction. Predictions are made by walking the splits of the tree
until arriving at a leaf node and output the class value at that leaf
node.

SVM: In this algorithm, we plot each data item (tweet) as a point in
n-dimensional space (where n is number of features) with the value
of each feature being the value of a coordinate (Support Vectors). A
hyperplane is a line that splits the input variable space. We apply
SVM learning algorithm because it finds the coefficients that results
in the best separation of the classes by the hyperplane.

# Code

https://bitbucket.org/davidnagilla/data-science/src/master/
