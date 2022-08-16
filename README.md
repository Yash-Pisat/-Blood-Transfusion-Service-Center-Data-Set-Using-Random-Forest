# Random Forest
Compilation of projects
Forest Trees
This project is a collaboration between me and Sneha khirwal.

Analysis
The analysis is based on the data published by University of california (UCI). It contains donor database of Blood Transfusion Service Center in Hsin-Chu City 
in Taiwan. Every three months, the center sends a bus with its blood transfusion service to a university in Hsin-Chu City to collect donated blood. To 
build a FRMTC model, we selected 748 donors at random from the donor database. Each of the 748 donor records included the following information: R (Recency - months since last donation), F (Frequency - total number of donations), M (Monetary - total blood donated in c.c.), T (Time - months since first donation), and a binary variable indicating whether the donor gave blood in March 2007. (1 stand for donating blood; 0 stands for not donating blood).

The purpose of the analysis of this dataset is to build a model to predict whether the person will donate the blood on the given date using Random Forest algorithm. To improve the accuracy, We did EDA and also determined the importance of the features. The features with highest impact are consider in training the model.

The steps we follow are :
Data Understanding
Data Visualization
Data Preparation
Modelling
Hyperparameter tuning
Evaluation
Contents of Repository
Superseded : Folder containing previous/unused work
Classification.py : Python file with classifcation class utilised in index.ipynb
Ensemble.py : Python file with ensemble class utilised in index.ipynb
Fores_trees.pdf : PDF containing project presentation
READMEmd : Markdown file with executive summay of project
covtype.csv : CSV file with data used for project
index.ipynb : Python Notebook containing main conent for project (code,visualisations,modelling,evaluation)
