# Assignment_No_1 Exploratory Data Analysis

# use housing.csv dataset

Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): CRIM: per capita crime rate by town

ZN: proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS: proportion of non-retail business acres per town

CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

NOX: nitric oxides concentration (parts per 10 million)

1https://archive.ics.uci.edu/ml/datasets/Housing

123

20.2. Load the Dataset 124

RM: average number of rooms per dwelling

AGE: proportion of owner-occupied units built prior to 1940

DIS: weighted distances to ﬁve Boston employment centers

RAD: index of accessibility to radial highways

TAX: full-value property-tax rate per $10,000

PTRATIO: pupil-teacher ratio by town 12. B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town 13. LSTAT: % lower status of the population

MEDV: Median value of owner-occupied homes in $1000s

We can see that the input attributes have a mixture of units.

It has 13 inputs and last column is output which indicates house price. 

Read the dataset using pandas 

Display first 10 rows of it

Display mean value of all the input columns 

Display deviation of all input columns using Boxplot visualization

Estimate correlation of each input variable with output, list five most important variables based on the correlation 

Draw five scatter plots to show correlation between each of the above five variables and output