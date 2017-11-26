# Titanic - Exploratory Data Analysis 
# Model used - Linear Regression

### Dataset 
Obtained from Kaggle : https://www.kaggle.com/c/titanic/data

I took 'train.csv' and separated the training data itself into 80/20 to fit my linear regression model.

Python Jupyter Notebook : https://github.com/yuvaraja402/Titanic_EDA/blob/master/Titanic%20EDA.ipynb

### What I did ?
1.Data was little messy so had to remove 'NaN' containing rows.

2.There were rows without age,so took mean of all ages in dataset and filled the 'NaN' ages. Mean was 29.50 -> round value 30.

3.Observations written in comment lines within jupyter notebook.
Only 38 % people survived the crash.
Older people of age above 45 didnt make it much after accident.

4.One thing observed which was weird - I have heard that women and kids left early after the accident before men,large percentage of men had lost their lives.

5.Created linear regression model and fitted data. Train and test data into 80/20 split.Target was to predict the chances of survival (0-died,1-survived) from features (age,sex,fare).Included fare as feature since rooms positions differed according to their ticket classes and room of third class ticket was way down for a person to escape during accident.

6.Model had accuracy of 77 % prediction when tested with test data.
