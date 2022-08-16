# Random Forest for Classification for Regression 
This project is a collaboration between me and Sneha khirwal.

## Analysis
The analysis is based on the data published by University of california (UCI). It contains Synchronous machine data obtained in real time from the experimental operating environment. These are the attributes provided in the dataset: Iy (Load Current), PF (Power factor), e (Power factor error), dIf (Changing of excitation current of synchronous machine), If (Excitation current of synchronous machine).

The purpose of the analysis of this dataset is to build a model to  estimate the excitation current of Synchronous Machine using Random Forest algorithm. To improve the accuracy, We did EDA and also determined the importance of the features. The features with highest impact are consider in training the model.

## The steps we follow are :
1. Data Understanding
2. Data Visualization
3. Data Preparation
4. Modelling
5. Hyperparameter tuning
6. Evaluation

## Contents of Repository
- ``Random Forest Regression.py `` :   Python file with classifcation class utilised in index.ipynb
- ``READMEmd  ``         :   Markdown file with executive summay of project
- ``SynchronousMachine.csv  ``      :   CSV file with data used for project
- ``Regression Documention.py  ``      :   Documentation for the code implemented
- ``index.ipynb   ``     :   Python Notebook containing main conent for project (code,visualisations,modelling,evaluation)
