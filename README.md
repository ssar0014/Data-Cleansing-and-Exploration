# Data-Cleansing-and-Exploration

Environment: Python 3.6.8 and Jupyter notebook

Libraries used:
Basemap - To plot maps in Python
Matplotlib - Standard visualisation library used for plotting in python
Seaborn - Visualisation library used for plotting linear regression lines
NumPy - Library for Python, adding support for large, multi-dimensional arrays and matrices
Pandas - Software library written for the Python programming language for data manipulation and analysis
Math - Gives functionality of Trigonometric functions
NetworkX - Allows for the creation and usage of graphs and networks
Time - For the usage and arithmetic manipulation of date-time objects
Scikit-Learn - Machine learning library featuring various classification, regression and clustering algorithms


The following code works in 3 Parts:

The first part reads a dirty CSV data file with semantic and syntactical errors, and does various cleaning based on the errors found in them, and then writes it to a new CSV file,


The second part reads a CSV data file with missing value errors, makes a Linear Regression model based on certain parameters, and imputes values wherever they are missing. The cleaned data is then written to a new CSV file,


The third part reads a CSV data file with outlier errors, lists out the different outliers, removes them, and then writes the cleaned data to a new CSV file.

There are 3 input files with different kinds of errors, which are read, worked on, and returned as 3 output files with the errors cleaned.
