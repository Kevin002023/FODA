# FODA

By Kevin O'Leary

This repository is my submission for the module Fundamentals of Data Analysis as part of the Higher Diploma in Computing and Data Analytics at Atlantic Technological University. The repository contains the Jupyter Notebooks tasks.ipynb and project.ipynb


**Tasks**

We were given 5 different tasks corresponding to a topic presented for every two weeks of lectures. 


**Project Instruction**

- Create a notebook investigating the variables and data points within the well-known iris flower data set associated with Ronald A Fisher.
- Discuss the classification of each variable within the data set according to common variable types and scales of measurement in  mathematics, statistics, and Python.
- Select, demonstrate, and explain the most appropriate summary.
-  Select, demonstrate, and explain the most appropriate plot(s) for
each variable.

# How to download this repository

Go to the URL for the repository on GitHub at https://github.com/Kevin002023/FODA. Click the green code or download button


# **Software Used**
This project was done on Jupyter Notebooks using Python 3.11.15. on the editor Visual Studio Code V 1.75.1. It was used to produce both the code and this README.md file.

The original dataset used is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

The packages I used are;

````
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns
import shapiro from scipy.stats
````

Pandas allows you to manipulate the dataset as a dataframe. It was used to import the dataset, set up a dataframe, validate the values and then for aggregation and grouping of specific variables. I made extensive use of the Pandas documentation which can be found [here](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html)

NumPy was used for mathematical operations and when working with arrays/matrices. Its documentation can be found [here](https://numpy.org/doc/stable/)

Matplotlib is an extension of NumPy and was used to present the data in plots. Its documentation is [here](https://matplotlib.org/stable/index.html)

Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. Its documentation can be found [here](https://seaborn.pydata.org/tutorial.html)

SciPy.stats is a module that contains a large number of probability distributions, summary and frequency statistics, correlation functions and statistical tests, masked statistics, kernel density estimation. Its documentation can be found [here](https://docs.scipy.org/doc/scipy/reference/stats.html)

# Contents of Repository
- This Readme file
- tasks.ipynb -a notebook containing the 5 assessments and their corresponding analysis.
- project.ipynb notebook which contains all of the research, analysis and plots formed. 
- a .gitignore fileto ignore any temporary files and folders that should not normally be committed to a repository

# References

References are noted in the section in which they are used and are listed at the end of the notebook. There are some references listed which are not used directly in the notebook but which were used to gain an understanding of the topics involved.