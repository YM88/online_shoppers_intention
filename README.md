### Click the following links to view the notebooks in NBViewer
[001_ETL](https://nbviewer.jupyter.org/github/YM88/online_shoppers_intention/blob/master/001_ETL.ipynb)  
[002_EDA](https://nbviewer.jupyter.org/github/YM88/online_shoppers_intention/blob/master/002_EDA_TRANSFORM.ipynb)  
[003_CLUSTERING](https://nbviewer.jupyter.org/github/YM88/online_shoppers_intention/blob/master/003_CLUSTERING.ipynb)  
[004_CLASSIFICATION](https://nbviewer.jupyter.org/github/YM88/online_shoppers_intention/blob/master/004_CLASSIFICATION.ipynb)




# Welcome to the Data Science Code Challenge
 The next part of our interview process is a code challenge that will give you the opportunity to show us how you solve data science problems.
 
  The description of our challenge is below &mdash; keep in mind that this is not a test, and there aren't "right" or "wrong" answers. It's merely meant to demonstrate your creativity, your hypothesis testing skills, your Python programming and communication abilities, and your familiarity with data science techniques and tools. 
  
  The challenge is not timed; generally we ask that candidates return their challenge within a week, but if you need more time, just let us know.

## From Clustering to Classification:

Oftentimes we receive a data set that is not yet suited for supervised machine learning because it lacks the necessary target. In these cases, we can sometimes use clustering to extrapolate categories and then use the cluster labels for downstream classification. For this challenge, we'd like to see how you do at this kind of task.

Create a fresh Python project (either `.py` or `.ipynb`) that does the following:
 - [x] Downloads a clustering data set from the UCI Machine Learning Repository.
 - [x] Performs clustering on the data. _Note: Please include an explanation of why you selected that particular clustering algorithm for this problem._
 - [x] Plots the clusters and provides a textual interpretation of the results.
 - [x] Transforms the cluster labels into target variables for classification.
 - [x] Performs classification on the data using the new categorical target values. _Note: please include an explanation of why you selected that particular classification algorithm._
 - [x] Evaluates the performance of the classifier and provides some textual interpretation.
 - [x] Includes a sketched-out diagram (e.g. using Google draw or on paper/whiteboard) of a pipeline that integrates the above steps so that the model could be rebuilt on demand (e.g. in a production environment).

Save your file(s), upload them to a Github repository, and send us the link!