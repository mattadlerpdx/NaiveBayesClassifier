# NaiveBayesClassifier
This program implements the Gaussian Naive Bayes classifier.
Input:

spam/not spam emails. Each email has number of features (number of columns). Each row represents an email. 

Algorithm:

Compute the mean for each feature give a class (each column). Store features for each column in a spam/notSpam array.

Compute mean probabilities(post-probablities) from GaussianNB formula: 


<img width="712" alt="Screen Shot 2022-08-31 at 11 17 17 AM" src="https://user-images.githubusercontent.com/63027273/187750636-048edd95-0ac8-451e-8ae7-35042e7dc776.png">

