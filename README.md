# NaiveBayesClassifier
This program implements the Gaussian Naive Bayes classifier.
Input:

spam/not spam emails. Each email has number of features (number of columns). Each row represents an email. 

Algorithm:

Compute the mean for each feature given a class (each column). Store features for each column in a spam/notSpam array.

Compute mean probabilities(post-probablities) from GaussianNB formula: 

<img width="711" alt="Screen Shot 2022-08-31 at 11 19 37 AM" src="https://user-images.githubusercontent.com/63027273/187751054-85800a40-519e-4157-bca6-8a0664adcb94.png">




<img width="712" alt="Screen Shot 2022-08-31 at 11 17 17 AM" src="https://user-images.githubusercontent.com/63027273/187750636-048edd95-0ac8-451e-8ae7-35042e7dc776.png">

To Run File:

- Install Jupyter Notebook: If you haven't installed Jupyter Notebook on your computer, you can do so by following the instructions on their website: https://jupyter.org/install
- Open Jupyter Notebook: Once you have installed Jupyter Notebook, open it by typing jupyter notebook in your terminal or command prompt.
- Navigate to the directory containing the .ipynb file: In Jupyter Notebook, navigate to the directory where the .ipynb file is located.
- Open the .ipynb file: Click on the .ipynb file to open it in Jupyter Notebook.
- Run the code: You can run the code in the .ipynb file by clicking on the "Run" button or by pressing "Shift + Enter" on your keyboard. You can also run all the code in the notebook by clicking on "Cell" in the menu bar, then "Run All."
