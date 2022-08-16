# Data-Science
Compilation of projects
Forest Trees
This project is a collaboration between me and Sneha khirwal.

Analysis
The analysis is based on the data published by University of california (UCI). It contains donor database of Blood Transfusion Service Center in Hsin-Chu City 
in Taiwan. Every three months, the center sends a bus with its blood transfusion service to a university in Hsin-Chu City to collect donated blood. To 
build a FRMTC model, we selected 748 donors at random from the donor database. These 748 donor data, each one included R (Recency - months since last 
donation), F (Frequency - total number of donation), M (Monetary - total blood donated in c.c.), T (Time - months since first donation), and a binary variable 
representing whether he/she donated blood in March 2007 (1 stand for donating blood; 0 stands for not donating blood).

These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices.

The purpose of our analysis is to determine a model based on those categorical features and provide our customer with a tool to identify possible areas to grow Lodgepole Pine with the least human intervention. Our customer would like to explore areas outside this particular forest, therefore we would remove from the dataset the relevant columns regarding specific areas of this forest and check if we obtain a good prediction model.

The steps we follow are :
Data Understanding
Data Visualization
Data Preparation
Modelling
Baseline Model via Logistic Regression
Optimised Logistic Regression
Optimised Decision Tree
Optimised Random Forest
Adaboost
XGBoost
Voting
Stacking
Model Selection
Threshold Selection
Evaluation
Contents of Repository
Superseded : Folder containing previous/unused work
Classification.py : Python file with classifcation class utilised in index.ipynb
Ensemble.py : Python file with ensemble class utilised in index.ipynb
Fores_trees.pdf : PDF containing project presentation
READMEmd : Markdown file with executive summay of project
covtype.csv : CSV file with data used for project
index.ipynb : Python Notebook containing main conent for project (code,visualisations,modelling,evaluation)
