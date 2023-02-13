# Data analysis with python and pandas

Welcome to Exploratory Data Analysis With Python and Pandas.
In this project, I applied practical Exploratory Data Analysis (EDA) techniques on tabular dataset using Python packages 
such as Pandas and Numpy. Also, Produced data visualizations using Seaborn and Matplotlib.

# Project Objectives

In this Project, we are going to focus on three learning objectives:

1. Apply practical Exploratory Data Analysis (EDA) techniques on any tabular dataset using Python.
2. Produce data visualizations using Seaborn and Matplotlib
3. Identify and handle duplicate and missing data

# Project Structure

The hands on project on **Exploratory Data Analysis With Python and Pandas** is divided into following tasks:

**Task 1: Initial Data Exploration**

1. In this task, we are introduced to the project and learning outcomes.
2. Once we are familiarized with the Rhyme interface, we begin working in Jupyter Notebooks, a web-based interactive computational environment 
   for creating notebook documents.
3. Next, we will import essential libraries such as NumPy, Pandas, Seaborn, Matplotlib and so on. We use Pandas to read in the data, get a brief glimpse 
   of the first few rows, and calculate some quick summary statistics of the numeric columns.

 **Task 2: Univariate Analysis**

1. In this task, we conduct univariate analysis on both continuous and categorical variables.
2. We first plot the distribution of customer ratings with seaborn and also overlay the mean, 25th and 75th percentile quantiles calculated using Numpy.
3. We then use Pandas' .hist() method to plot the distribution for all numeric variables.
4. Using Seaborn's .countplot() method, we see the frequency distribution of 'Branch' and 'Payment' which are categorical variables.

**Task 3: Bivariate Analysis**

1. In this task, we conduct bivariate analysis on both continuous and categorical variables.
2. We use Seaborn to plot scatterplots and regression plots to identify the relationship between customer rating and gross income.
3. Additionally, we use Seaborn to plot a boxplot to check the difference in aggregate sales figures between the three branches of supermarkets, and to compare sales patterns between men and women.
4. We plot a time series graph to check for trends in gross income over a period of three months.

**Task 4: Dealing With Duplicate Rows and Missing Values**

1. In this task, we identify and deal with duplicate rows and missing values in our dataset.
2. We calculate the number of duplicate rows and delete them using Pandas.
3. We then do the same with missing values, but instead of deleting those rows, we replace missing values by the means of their respective columns.
4. We explore our dataset using Pandas Profiler to see how we can automate a lot of exploratory data analysis given certain conditions are met.

**Task 5: Correlation Analysis**

1. In this task, we conduct correlation analysis on the numeric variables in our dataset.
2. We use Numpy to calculate the correlation between two numeric variables.
3. We then use pandas to calculate a correlation matrix to show all pairwise correlations of numeric variables.
4. Finally, we use seaborn to plot the calculated correlation matrix as a heatmap that is easily interpretable.




