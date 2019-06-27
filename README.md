# Comment Text Classification

## Description
The project consists in finding the right supervised model and its parameters to distinguish the type of a comment on Wikipedia. 
In the first part of the code the input data are transformed using the tf-idf algorithm.
The models used are MultinomialNB and Logistic Regression.
The metrics used in order to evaluate the models are Roc_Auc, F1, Recall.

## Prerequisites
In order to run the file projectML.ipynb you need to intall Anaconda. You can find Anaconda distribution at this link: https://www.anaconda.com/distribution/

## Dataset
The datasets are available here: https://www.dropbox.com/sh/e17taxpg3js3com/AAAjVAlB5LhcNrHrc9KWvgRRa?dl=0
You just need to download them and to put the right path in the 'read_csv()' function.
