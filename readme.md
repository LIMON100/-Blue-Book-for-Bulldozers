# Blue Book for Bulldozers

## Problem Description:

For this competition, you are predicting the sale price of bulldozers sold at auctions.

The data for this competition is split into three parts:

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
The key fields are in train.csv are:

SalesID: the uniue identifier of the sale
MachineID: the unique identifier of a machine.  A machine can be sold multiple times
saleprice: what the machine sold for at auction (only provided in train.csv)
saledate: the date of the sale
There are several fields towards the end of the file on the different options a machine can have.  The descriptions all start with "machine configuration" in the data dictionary.  Some product types do not have a particular option, so all the records for that option variable will be null for that product type.  Also, some sources do not provide good option and/or hours data.
The machine_appendix.csv file contains the correct year manufactured for a given machine along with the make, model, and product class details. There is one machine id for every machine in all the competition datasets (training, evaluation, etc.).



## Dataset:

https://www.kaggle.com/c/bluebook-for-bulldozers/data



## Working Procedure:

Divided the work into 4 major part.

### 1 . EDA(Exploratory Data Analysis)

In this part mainly visualize the dataset with different expect.Try to find out the which columns are important, is there any relation between them or many more things.

### 2 . Feature Engineering

Create some new features from the existing one to find out better outcome.


### 3 . Data Preprocessing

Delete the unnecessary columns and divided into train and test.


### 4 . Apply Model

In this project there only two ML algorithms apply.
