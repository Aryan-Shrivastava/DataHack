# DataHack

## Problem Description
Our goal is to predict how likely individuals are to receive their xyz and seasonal flu
vaccines. Specifically, you'll be predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine.

## Getting Started
My repository contains the following :
* **submission_file.csv** : 
This is my main submission file. It contains the final probabilities of receiving the xyz_vaccine and seasonal_vaccine for the test_set_features.
+ **Problem Description** : Contains the pdf for problem description as given in the Hackathon.
* **Notebooks (Folder)** : Contains another two folders: 
    * **xyz_flu** :  
    Contains the:

        * Jupyter notebook 'xyz_flu.ipynb' in which data cleaning and transformation was done.

        * csv file 'xyz.csv' contains the cleaned features from the original training_set_features given.

        * Jupyter notebook 'xyz_flu_model.ipynb' contains the model for prediction of receiving the xyz flu vaccine.
    
    * **seasonal_flu** :  
    Contains the:

        * Jupyter notebook 'seasonal_flu.ipynb' in which data cleaning and transformation was done.

        * csv file 'seasonal.csv' contains the cleaned features from the original training_set_features given.

        * Jupyter notebook 'seasonal_flu_model.ipynb' contains the model for prediction of receiving the seasonal flu vaccine.

* **dataset (Folder)** :   
This folder contains the datset given in the hackathon:
    * test_set_features.csv
    * training_set_features.csv
    * training_set_labels.csv

## Results obtained
* The ROC AUC score for the model used for prediction of receiving the seasonal vaccine is 0.8239883648067448

* The ROC AUC score for the model used for prediction of receiving the xyz_flu vaccine is 0.8187068762658734

* Combined ROC AUC score : 1.642695241
