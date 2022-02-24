# Objective of Homework Assignment

**Classification:** In this problem, you are asked to write a report to summarize your analysis of the
popular \Auto MPG" data set in the literature. Much research has been done to analyze this data
set, and here the objective of our analysis is to predict whether a given car gets high or low gas
mileage based 7 car attributes such as cylinders, displacement, horsepower, weight, acceleration,
model year and origin.

The \Auto MPG" data set is available at UCI Machine Learning (ML) Repository. There are 398 rows (i.e., 398 different kinds of cars), and 9 columns (the car attributes and
name): https://archive.ics.uci.edu/ml/datasets/Auto+MPG

**A** Create a binary variable, mpg01, that contains a 1 if mpg contains a value above its median,
and a 0 if mpg contains a value below its median. This binary variable will be the response variable
in this homework. Note that you need to frst compute the median value of the mpg variable in the
data set.

**B** Explore the data graphically in order to investigate the association between mpg01 and the
other features. Which of the other features seem most likely to be useful in predicting mpg01?
Scatterplots and boxplots may be useful tools to answer this question. Describe your fndings.

**C** Split the data into a training set and a test set. Any reasonable splitting is acceptable, as
long as you clearly explain how you split and why you think it is reasonable. For your convenience,
you can either randomly split, or save every fifth (or tenth) observations as testing data.

**D**For the purpose of this homework, perform the following classiffcation methods on the
training data in order to predict mpg01 using the variables that seemed most associated with mpg01
in (c). What is the test error of the model obtained?

(1) LDA, (2) QDA, (3) Naive Bayes, (4) Logistic Regression, (5) KNN with several values of K.

Write a report to summarize your fndings, e.g., what is the best method and how to use your
results in the context of guiding to manufacture or buy high gas mileage cars. The report should
include (i) Introduction, (ii) Exploratory (or preliminary) Data Analysis, (iii) Methods,
(iv) Results and (v) Findings. Please attach your computing code for R, Python, or other
statistical software (without, or with limited, output) in the appendix of your report, and please
do not just dump the computer output in the body of the report. It is important to summarize
and interpret your computer output results.
