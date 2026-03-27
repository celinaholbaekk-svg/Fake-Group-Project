# Fake-Group-Project
## Project description

This project builds a fake news detection system using the FakeNewsCorpus dataset. First, the dataset is cleaned by applying tokenization, stopword removal, and stemming. Then, the dataset is divided into 80\% training, 10\% validation, and 10\% test data.

We also develop a simple logistic regression model to evaluate the data using the F1-score. In addition, we build a more advanced model using a Support Vector Machine and TF-IDF features. 

Finally, the models are evaluated on both the FakeNewsCorpus and LIAR datasets.

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

# Data
This project uses multiple datasets obtained from Absalon:

News Sample dataset – used to develop and test the preprocessing pipeline before applying it to the full FakeNewsCorpus
FakeNewsCorpus (995K subset) – used for training and evaluation
LIAR dataset – used to evaluate model performance on an external dataset

The trained model was evaluated on the LIAR dataset without retraining.

# Results
From Part 2
Logistic Regression -0.88
Advanced: 

Results From part 4 using the model from part 3
for the Fakenews dataset using the advanced model = unknown 
for the LIAR dataset using the simple model = unknonw
for the LIAR dataset using the advanced model = unknown


