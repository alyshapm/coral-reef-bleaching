# NOAA_ReefCheck
This folder contains related files for the NOAA Reef Check & Coral Bleaching dataset that can be found in the datasets folder.

# Contents
- [Dataset Preparation and Preprocessing](./NOAAPrep.ipynb)
- [Prepared Dataset](./NOAA_int.csv)
- [Data Visualization](./DataVisualization_NOAA.ipynb)
- [Regression & Features Importance](./Regression_NOAA.ipynb) 
- [Decision Tree Algorithm](./DecisionTree_NOAA.ipynb)
- [SVM Algorithm](./SVM_NOAA.ipynb)
- [Naive Bayes Algorithm](./NaiveBayes_NOAA.ipynb)

# Brief Explanation
Some of the machine learning algorithms do not accept object as a datatype, and the dataset majorly contains objects.
The dataset was prepared and preprocessed to change the datatypes from objects to int or float.
This process can be found in NOAAPrep.ipynb.

The prepared dataset was then exported, which is NOAA_int.csv

The dataset was analyzed through the use of data visualization, which can be seen in DataVisualization_NOAA.ipynb.
This was done to fully understand the contents of the dataset and the distribution of its variables.

The three remaining files are different algorithms used for the dataset, indicated by their names.
