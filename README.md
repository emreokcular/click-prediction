# click-prediction

## About Me

I am Emre Okcular, a data science intern at [Dictionary.com](https://www.dictionary.com/) Currently pursuing [Master of Science in Data Science](https://www.usfca.edu/arts-sciences/graduate-programs/data-science) at University of San Francisco.

## Project Goal

This repo includes dataset and jupyter noteboook file for the Final Project for MSDS 699 - Machine Learning Lab course. Since click prediction is one of the main business case for most of the tech companies, it is selected as the topic of this project.

## Dataset

Dataset is downloaded from https://www.openml.org/d/1226 . It is used also in 2012 KDD Cup.

## Summary

Different models from sklearn such as RandomForestClassifier, ExtraTreesClassifier and LogisticRegression
are used for predicting clicks of ads. The hyperparameters of models are tuned with grid search methods. You can see the scores below.

* Three Modeling Approach
    * LogisticRegression
    * RandomForestClassifier
    * ExtraTreesClassifier

**Models**|**Hyperparameters**|**accuracy\_score**|**f1\_score**
:-----:|:-----:|:-----:|:-----:
RandomForestClassifier|sklearn default|0.833|0.881
LogisticRegression with Randomized Grid Search|See notebook|0.832|0.908
RandomForestClassifier with Randomized Grid Search|See notebook|0.839|0.898
ExtraTreesClassifier with 5 fold CV|sklearn default|0.825|0.536