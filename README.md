# Campus Placement Analysis
Applying various Machine Learning algorithms to check if a student will be placed or not.

## What is in it?
This data set consists of Placement data of students in our campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students.

## Questions:
- Which factor influenced a candidate in getting placed?
- Does percentage matters for one to get placed?
- Which degree specialization is much demanded by corporate?

## Data Overview:
- This dataset is taken from [Kaggle](https://www.kaggle.com/benroshan/factors-affecting-campus-placement)
- This dataset has 14 columns: ['gender', 'ssc_p', 'ssc_b', 'hsc_p', 'hsc_b', 'hsc_s', 'degree_p','degree_t', 'workex', 'etest_p', 'specialisation', 'mba_p', 'status', 'salary'].

## Plotting the problem as a ML problem
```status``` variable is a binary variable. 
This problem is a binary classification problem - for a given set of features we need to see if a student is placed or not.
performance Metrics: accuracy_score

```diff
- please look for Campus Placement Analysis.ipynb for implementation.
```
