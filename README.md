# Fake-Group-Project

# Project description
This project will build a fake news detection, using the fake news data set. 
Firstly the dataset will be cleaned by applying tokenization, stop word removal and stemming.
secondly the data set will be divided into 80% training 10% test and 10% validation.

We have also devolped a simple logistic model to evaluate the model using the F1 score on the 10% test and 80% train of the data set.
Then we have build a more advanced model combining support vector machine and TF-IDF.
and then the dataset fakenews and LIAR will be applied to the advanced model using SVM and TF-IDF features, and we will evalute the F1 score from the datasets.

# installation instructions 
pip install pandas, nltk, numpy, matplotlib, pandarallel, pyarrow, jupyter,
Vs code

# Usage 
You should run the project in the followung order
run part 1
to run part 2, 
to run part 3
to run part 4

# DATA
In this project we have used the FakeNewsCorpus containing 995.000 rows, downloaded from absalon

# Results
From Part 2
Logistic Regression -0.88
Advanced: 

Results From part 4 using the model from part 3
for the Fakenews dataset using the advanced model = unknown 
for the LIAR dataset using the simple model = unknonw
for the LIAR dataset using the advanced model = unknown


