# Fake-Group-Project
# Project description
This project tries to build a fake news detection system, using the fake news data set.

The process starts with preprocessing the dataset, which includes tokenization, stopword removal and stemming to prepare the text data for analysis.
The dataset is then split into three parts: 80% for training, 10% for testing, and 10% for validation.

We have also devolped a simple logistic model to evaluate the model using the F1 score on the 10% test and 80% train of the data set.

First, a simple logistic regression model is developed to establish a baseline. The model is evaluated using the F1 score on both the training data (80%) and the test data (10%).

Next, a more advanced model is implemented by combining Support Vector Machines (SVM) with TF-IDF. This model is designed to improve classification performance on textual data.

Finally, both the Fake News dataset and the LIAR dataset are applied to the advanced SVM + TF-IDF model. The performance of the model is evaluated using the F1 score across these datasets to compare results and assess effectiveness.

# installation instructions 
For the code to work you have to pip install, pandas, nltk, numpy, matplotlib, pandarallel, pyarrow, jupyter, ipywidgets, scikit-learn and cleantext.
To run the code you would need either Vs code or Pycharm.
we are importing re, pandas as pd, numpy as np, matplotlib.pyplot as plt.
from pandarallel we import pandarallel and use pandarallel.initialize(progress_bar=True)
When importing nltk, we have to use from nltk.tokenize import word_tokenize, from nltk.corpus import stopwords
from nltk.stem import SnowballStemmer, nltk.stem import PorterStemmer and from sklearn.model_selection import train_test_split

pip install pandas nltk numpy matplotlib pandarallel pyarrow jupyter ipywidgets scikit-learn cleantext


# Usage 
You should run the project in the following order
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


