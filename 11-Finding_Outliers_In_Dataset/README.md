# Finding Outlier in a Dataset

CRITERIA TO IDENTIFY AN OUTLIER:
1. Data points that falls outside of 1.5 times of an interquartile range above the 3rd quartile and below the 1st quartile.
IQR = Q3 - Q1
       = 75% - 25%

2. Data points that falls outside of 3 standard deviations. we can use z-score and if the z score falls outside of 2 standard deviation.

Suppose, X = [1,2,3,4,5] mean= 3 and std_Dev = 1
z = Xi - mean/std_dev. If any data point lies away from z<=3, it is know as outlier.

VARIOUS WAYS OF FINDING THE OUTLIER
1. Using Scatter plots
2. Box Plots
3. Using z score
4. Using the IQR interquantile range
