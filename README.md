# Udacity-Capstone-Project
## Motivation
The goal of this project is to create a machine learning model that can predict whether an employee will leave a mid-sized company based on their level of happiness, performance, workload, and experience. The end result will be a trained model saved as a .pkl file. Additionally, the project will rank the features based on their importance in predicting employee churn.
## Requirements, files and data
Project files required for the project:

EmployeeChurnNotebook.ipynb,
employee_data.csv,
Software required to run these files:
Download the latest version of Anaconda here: https://www.anaconda.com/products/individual
Anaconda contains Python 3.7 and the data science-centric IDE JupyterLab.
Load EmployeeChurnNotebook.ipynb in JupyterLab and run all cells.
This will create the following files:

Modelling table 1.csv,
model_v1.pkl,
Modelling table 2.csv, (final ABT for modelling).
model_v2.pkl (final trained model file).
## Results
The machine learning model created as part of this project has been trained and saved as model_v2.pkl, and it achieved an impressive AUROC score of 99%. The three most important features in predicting employee churn were found to be n_projects (workload), satisfaction (happiness), and tenure (experience), and a full list of feature importance can be found in both the .ipynb notebook and the corresponding blog post. The project also revealed a number of interesting insights from the exploratory data analysis performed on the dataset, which are detailed in both the notebook and the blog post.
# Blog post link
https://medium.com/@dilupac/udacity-data-scientist-capstone-project-4ab8ee8a3b8c
