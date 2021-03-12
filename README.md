# click-prediction

## About Me

I am Emre Okcular, a data science intern at [Dictionary.com](https://www.dictionary.com/) Currently pursuing [Master of Science in Data Science](https://www.usfca.edu/arts-sciences/graduate-programs/data-science) at University of San Francisco.

## Project Goal

This repo includes dataset and jupyter noteboook file for the Final Project for MSDS 699 - Machine Learning Lab course. Since click prediction is one of the main business case for most of the tech companies, it is selected as the topic of this project.

## Dataset

Dataset is downloaded from https://www.openml.org/d/1226 . It is used also in 2012 KDD Cup.

## Summary

Different models from sklearn such as RandomForestClassifier, ExtraTreesClassifier, IsolationForest, LogisticRegression, DecisionTreeClassifier are built with hyperparameter combinations. Finally, ...

* Three Modeling Approach
    * LogisticRegression Only
    * RandomForestClassifier
    * ExtraTreesClassifier

**Models**|**Parameters**|**accuracy\_score**|**f1\_score**
:-----:|:-----:|:-----:|:-----:
LogisticRegression|sklearn default|0.83|0.91
LogisticRegression with Randomized Grid Search| |0..84|0.91
RandomForestClassifier|sklearn default|0.83|0.91
RandomForestClassifier with Randomized Grid Search| |0.83|0.91
ExtraTreesClassifier with 5 fold CV|sklearn default|0.82|0.53