# Car Price Prediction

This project contains the code for Pre-Processing the Dataset and applying the Random Forest Regressor Algorithm for predicting the Car Price using Python3, JupyterNotebook. 

In this study we employ a small dataset collection using data on the prices of other cars and their characteristics to build car price prediction models. 
The output given models will help us determine the most reasonable car selling price. 

Dependency Libraries:
```
* Python 3
* pandas
* numpy
* scipy
* scikit-learn
* matplotlib
* seaborn
* jupyter notebook
```
   
Project Outline:
```
- Data Preparation
- Data Wrangling
- Data Exploration
- Model Development
- Model Evaluation and Refinement
```

Pre Processing Steps Followed:
```
1. Identifying Null Values.
  -No Null Values were found.
2. Plotting Histogram to find the Data Point's Distribution.
3. For each feature, identifying Outliers.
4. Outliers Treatment using IQR Method for each feauture.
```
Machine Learning Steps Followed:
```
1. The required libraries are imported.
2. Tha Dataset is read in Jupyter Notebook.
3. Correlation Matrix is formed.
4. Dropping columns that doesn't affect the output variable.
5. One-Hot Encoding categorical variables in columns that affect the output variable.
6. Train, Test Split is done.
7. Feature Scaling is performed.
8. Fitting the model to random forest regressor.
9. Performance metrics of the algorithm is found.
```
# The used Random Forest Regressor Model gives a R2 Score of 0.8202 which is nearly equal to the accuracy of 82.02%.
