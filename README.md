# knn
Created a KNN algorithm to identify spam

In this project we were given a dataset with a bunch 
of features and labels for spam and not spam emails.
My task was to create a KNN algorithm (from scratch) to identify the spam emails, 
and evaluate the accuracy. 

I did the following steps:
1) Evaluated and cleaned the data
2) Created a function to efficiently calculate euclidian distance for each observation
3) Created a function to assess accuracy of the model
4) Designed the algorithm to run on various k values, and used the most accurate one for the final model
5) Repeated steps 1-4 after the data had been normalized to measure impact
6) Output was a sample of 50 observations with their nearest neighbor classifications 
