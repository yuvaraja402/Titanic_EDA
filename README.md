# Titanic :ship: - Exploratory Data Analysis :mag_right: 
## Model used - Linear Regression

<b>Objective</b> :dart: - <i>To analyze the depth in tragic loss of people during the crash and analyse factors that had correlations.</i> 

### Quick links :link::
[Dataset](https://www.kaggle.com/c/titanic/data) from Kaggle

[Python Jupyter Notebook](https://github.com/yuvaraja402/Titanic_EDA/blob/master/Titanic%20EDA.ipynb) contains all analysis and visualization charts.

### Implementation Overview :
  1. Data cleaning
  2. Data wrangling
  3. Data Analysis

### Analysis :mag::
1. Only <b>38 % people</b> survived the crash. 
2. A group of <b>older people of age above 45</b> didnt make it from the crash.
2. Women and kids left early before the accident, huge percentage of <b>men had lost their lives</b>.
3. Created <b>linear regression model</b> and fitted data. Train and test data into 80/20 split.Target was to predict the chances of survival (0-died,1-survived) from features (age,sex,fare).<i>Included fare as feature since rooms positions differed according to their ticket classes and room of third class ticket was way down for a person to escape during accident.</i>
4. Regression model had accuracy of <b>77 % </b> prediction when validated with real data.
