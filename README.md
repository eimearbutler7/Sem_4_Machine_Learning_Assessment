# Semester 4 Machine Learning Assessment 
<img align="right" src="https://www.kdnuggets.com/images/cartoon-recommendation-python-machine-learning.jpg" width="200">

This repository contains Machine Learning and Statistics Assessment Q4 2019 (5 credits)

The primary document is the Jupyter Notebook "Boston House Prices.ipynb".

To run this document you must have installed software to run python code (https://www.python.org/), for example the Anaconda package (https://www.anaconda.com/) as well as keras.io set up to run with Tensorflow backend.

By running each cell in succession, it will import and assess the publicly available Boston House Price DataSet (1978). Once the characteristics of the set are reviewed, it will then assess if the price of homes are influenced by being beside the Charles River and create a Karas generated neural network to estimate the MEDV (median price) from a number of known parameters.  

The notebook sections are as follows: 
<img align="right" src="https://raw.githubusercontent.com/eimearbutler7/Sem_4_Machine_Learning_Assessment/master/z_section%204b.png" width="400">
- Introduction
- Section 1: The CHAS & MEDV Relationship
- Section 2: Broader Analysis of the Dataset
- Section 3: Further Investigation LSTAT vs MDEV and RM vs MDEV
- Section 4: Developing the Neural Network with Keras
= Section 4a - Preparing the data
- Section 4b - Creating a Neural Network for LSTAT vs MEDV
- Section 4c - Creating a Neural Network for PTRATIO vs MEDV
- Section 4d - Creating a Neural Network for both PTRATIO and LSTAT vs MEDV
- Section 4e - Creating a Neural Network for PTRATIO, TAX, AGE and LSTAT vs MEDV
- Conclusion
<img align="left" src="https://raw.githubusercontent.com/eimearbutler7/Sem_4_Machine_Learning_Assessment/master/z_section%204e.png" width="400">

The dataset connected with this jupyter notebook is available from numerous locations including from sklearn.datasets import load_boston .


A summary of the assessment criteria has been included below for reference:

**(20%) Describe:** Create a jupyter notebook that uses descriptive statistics and
plots to describe the Boston House Prices dataset.


**(20%) Infer:** use inferential statistics to analyse whether there is a significant difference 
in median house prices between houses that are along the Charles river and those that aren’t. 

**(60%) Predict:** Use keras to create a neural network that can predict the median house price 
based on the other variables in the dataset.
