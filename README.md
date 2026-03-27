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
To run this project, install the required Python packages using the following command:

pip install: pandas, nltk, numpy, matplotlib, pandarallel, pyarrow, jupyter, ipywidgets, scikit-learn, cleantext

It is recommended to run the project in either Visual Studio Code or PyCharm, or alternatively using Jupyter Notebook.

Before running the project, make sure to download the required NLTK datasets:

import nltk
nltk.download('punkt')
nltk.download('stopwords')

# Usage 
The project is divided into multiple parts. To reproduce the results, run the files in the following order:

Part 1
Part 2
Part 3
Part 4

# DATA
This project uses multiple datasets obtained from Absalon:

News Sample dataset – a smaller dataset used for testing and experimentation
FakeNewsCorpus – contains approximately 995,000 rows and is used as the primary dataset
LIAR dataset – used to evaluate model performance on an additional, external dataset

These datasets are used to train, validate, and evaluate both the baseline and advanced models.


# Results
From Part 2
Logistic Regression -0.88
Advanced: 

Results From part 4 using the model from part 3
for the Fakenews dataset using the advanced model = unknown 
for the LIAR dataset using the simple model = unknonw
for the LIAR dataset using the advanced model = unknown


