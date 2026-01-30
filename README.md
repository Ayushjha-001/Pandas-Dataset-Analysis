This repository contains my Pandas practice assignment using the Titanic dataset.

The goal of this notebook was to strengthen my understanding of data selection, filtering, grouping, and aggregation using real-world data.

### Files in This Repository

Assignment_pandas.ipynb – Jupyter Notebook with all solutions

Titanic-Dataset.csv – Dataset file

README.md – Project description

### Dataset Source

The dataset was taken from Kaggle:

https://www.kaggle.com/datasets/yasserh/titanic-dataset

#### Column Selection

Displayed only the following columns:

Name

Sex

Age

Fare

Survived

#### Passenger Filtering

Selected passengers who:

Are female

Have Fare > 30

This was done using boolean indexing.

#### Group By & Aggregation

Grouped passengers by Pclass and computed:

Survival rate

Average Fare

Average Age

Used the .groupby() and .agg() methods for clean multi-column aggregation.

### What I Learned From This Assignment

Through this exercise, I improved my understanding of:

Selecting specific columns in a DataFrame

Filtering rows using multiple conditions

Boolean indexing in Pandas

Grouping data using groupby()

Aggregating with multiple statistics

Renaming output columns for clarity

Calculating percentages after aggregation

I also learned how to:

Structure notebooks for GitHub submission

Work with real datasets instead of toy examples

Write cleaner and more readable Pandas code
