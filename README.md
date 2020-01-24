# MANE 6399 - Data Science in Manufacturing

## Homework 1 Assignment: Introduction to Python

### Assigned: January 23, 2020

### Due: January 31, 2020

Your first homework assignment focuses on an introduction to GitHub, Jupyter Notebooks and Python and Python packages. Please download the GitHub repository and work on your local machines. Once completed, please committ and push your local repository back to the master repository.

Your Homework 1 Repository should contain the following files: README.md, Homework1Assignment.ipynb, KaggleTitanticTrain.xslx.

---

#### Problem 1

Modify the code in cell 2 of the Homework1Assignment Jupyter Notebook. The original code calculates $P(Z<a)$. Your new version should calculate $P(Z>a)$. Also change the fill color from grey to another color of your choice and change the blue line lines to another color of your choice.

---

#### Problem 2

Expand upon the code in cell 3 to find the probability of outlier in Box Plot applied to exponential data with parameter $\lambda=0.01$.

##### Hints

1. Find the value of Q3,
2. Find the value of IQR,
3. Find the probability of an outlier, $F(Q_1-IQR)+(1-F(Q_3+IQR))​$
4. Make sure to print the values of Q1, Q3, IQR and probability of an outlier

---

#### Problem 3

In cell 4, you will analyze data from Kaggle Titanic training data set, KaggleTitanicTrain.xslx. Please perform the following tasks:
1. Use Panda to import the KaggleTitanicTrain.xslx file into a dataframe,
2. Used the describe command to calculate summary statistics for each variable,
3. Construct box plots for each variable, and
4. Construct a scatter matrix.