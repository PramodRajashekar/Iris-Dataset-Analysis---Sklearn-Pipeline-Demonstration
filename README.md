Sklearn Pipeline Demonstration using Iris Dataset
-------------------------------------------------

Introduction
------------
Most machine learning models require us to perform several data preprocessing steps such as feature scaling, PCA etc. as seperate lines of code before actually training the model on the data. This approach is not necessarily the best when it comes to code readability.
Machine learning pipelines can be very handy in this case as they enable a user to write and organize cleaner looking code and help with the ease of understanding. Also, when new data is introduced, the pipeline automatically performs all the necessary pre processing steps before training the model on the new data for further prediction - thereby iterating and automating all the processing steps
We will be using the iris flower dataset from the sklearn library in order to demonstrate a machine learning pipeline in this notebook and predict the species of the flower

About the Dataset
-----------------
Iris Flower Dataset
Data source: http://archive.ics.uci.edu/ml/datasets/Iris

Languages used
--------------
Python
