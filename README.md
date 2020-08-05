# NumPy and Pandas - Introduction

## Introduction

In this section, you'll be introduced to two libraries you will use extensively during your career as a Data Scientist: NumPy and Pandas!

Learning to use these libraries will form the foundation of your data processing work. Before you can apply machine learning algorithms or do interesting analyses, you often must clean and transform your data into a suitable format. Such initial data wrangling processes are often referred to as Extract Transform Load (ETL). Our primary tool of choice for performing ETL and basic analyses will be the Pandas package.

## Python and the Open-Source Movement

Now that we've learned some Python skills and have some Data Science knowledge, it's time to start gaining experience with the tools the professionals use. There are two programming languages that are heavily used in Data Science: Python and R. As you've probably surmised by now, we'll be focusing on Python. One of the great benefits of the Python language is that it has a very active open-source community, which means tons of great libraries and frameworks we can use to do the heavy lifting. One of the main reasons that Python is such a great choice for Data Science is that the scientific community has written plenty of great packages to do all advanced things we need. This means that when we use Python, we have access to a wealth of robust, effective tools written and maintained by an army of volunteers and professionals.

In this section, we're going to dig into two of the most foundational libraries in the Data Science toolbox --  **_NumPy_** and **_Pandas_**!

## The Data Science Stack: NumPy and Pandas

| <img src='https://github.com/learn-co-curriculum/dsc-numpy-and-pandas-intro/raw/master/numpy-logo.png'>  | <img src='https://github.com/learn-co-curriculum/dsc-numpy-and-pandas-intro/raw/master/pandas-logo.png' height=50% width=50%>  |
|---|---|

The two most foundational libraries in the Data Science 'Stack' are **_NumPy_** and **_Pandas_**.  In this section, we're going to dig into both libraries and get a feel for how they can make our lives easier and allow us to do amazing things with data with just a few lines of code.

### NumPy: Numerical Computation

The Python library that's most important to Data Scientists is almost certainly [NumPy](http://www.numpy.org/). NumPy is a _Numerical Computation_ Library, because it provides the building blocks for all of the other amazing Python libraries such as Pandas, in addition to providing a quick and easy way to do advanced mathematical computations. In a few short lessons, we're going to learn all about how NumPy works, how we can use it to quickly perform advanced math and computations, and how it fits into Data Science as a whole.

### Pandas: For Working With Data

[Pandas](https://pandas.pydata.org/) is a library for data analysis that makes Python a much more effective tool for Data Science. Pandas allows us to create **_DataFrames_** to organize and work with any dataset. You'll probably recognize DataFrames when you see them -- they look just like an Excel spreadsheet! In this section, we're going to get **A LOT** of practice in Pandas. You'll learn how Data Scientists use Pandas to quickly and effectively read, store, manipulate, and export data. The best part is, it's a one-stop shop since it is built on top of libraries like NumPy and Matplotlib!

## Why ETL?

ETL (extract, transform, load) is an essential first step to data analysis and data science. It also will form the foundation for exploratory data analysis. Often, you will be thrown a dataset that you have little to no information about. In these cases, your first step is to explore the data and get familiar with it. What are the columns? How many observations do you have? Are there missing values? Any outliers? If we have user-level data, how can we explore aggregate trends along features like gender, race, or geography? All of these can be answered by applying ETL to transform raw datasets into alternative useful views.

## Preview of ETL Techniques with Pandas

With Pandas, each of the following ETL steps can be achieved with 1 line each of Pandas code:

 - `pd.read_csv`: Loading data from a CSV (file) into a DataFrame (Python object)
 - `df.head`: Viewing all values for the first 5 rows of data
 - `df.groupby`: Group data by values in a given column
 - `df.duplicated`: Check for duplicates
 - `df.pivot`: Create a pivot table

## Summary

In this brief introduction, you learned some new vocabulary:

 - "NumPy" is a library for improved math and computation in Python
 - "Pandas" is a library for working with tabular data, which is built on top of NumPy
 - "ETL" means "Extract, Transform, Load".  It is the first step of any data science process, and Pandas has many useful built-in features for ETL

In the upcoming lessons you'll get a much richer understanding of these and other techniques for wrangling your data!
