# Responsible Data Science 
# Final Project Proposal

## Description and Goal
For our final course project, we examined an Automated Decision System (ADS) used to predict whether a data scientist is likely to seek a new job based on activity and survey responses conducted by a DS/AI learning platform. Using a set of features about a given data scientist, the ADS categorizes them as either “job seeking” or “non-job seeking”. The ADS, [published on Kaggle](https://www.kaggle.com/code/joshuaswords/awesome-hr-data-visualization-prediction/notebook), consists of data-preprocessing, data exploration, and model-fitting that utilizes SVMs, decision trees, random forests, logistic regressions, and KNNs to predict job-seeking status. Our aim is to design something of a "nutritional label" for this Automated Decision Systems that examines any potential bias in the data, the processing, and ultimate machine learning classification algorithm in determining job-seeking status.

## Data
[The data](https://www.kaggle.com/code/joshuaswords/awesome-hr-data-visualization-prediction/notebook) were published by a Data Science learning platform looking to hire data scientists who successfully completed some certification courses offered by the company. The algorithm is designed to understand the factors that lead a candidate to leave a current job for the purpose of potentially recruiting them as well as to provide valuable HR research for future hiring.

The model was trained on features corresponding to each candidate’s current credentials (education level, current company type and size, training hours completed…),  demographics (gender, city)  as well as work experience (years of relevant experience, years since last job…). Many of the features are categorical, some with high cardinality.  Several features contain missing data and had to be imputed.

The output of the ADS is a prediction of the probability of a candidate leaving a job as well as an interpretation of the factors affecting an individual’s decision.


## Motivation
We are interested in this dataset for a variety of reasons. First, as data scientists entering the workforce ourselves, we are interested in understanding the dynamics of the data science job market and the factors that influence our peers to seek new jobs. Second, the dataset is imbalanced, featuring many categorical variables and requiring making some assumptions around missing value imputation. As a result, we think that there are many opportunities to assess bias in data cleaning, technical bias in the prediction algorithm, and especially its performance on group fairness across different demographic groups.We are interested in this dataset for a variety of reasons. First, as data scientists entering the workforce ourselves, we are interested in understanding the dynamics of the data science job market and the factors that influence our peers to seek new jobs. Second, the dataset is imbalanced, featuring many categorical variables and requiring making some assumptions around missing value imputation. As a result, we think that there are many opportunities to assess bias in data cleaning, technical bias in the prediction algorithm, and especially its performance on group fairness across different demographic groups.


## Project Links and Resources
- Kaggle Description (https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists)
- Data set & Notebook (https://www.kaggle.com/code/joshuaswords/awesome-hr-data-visualization-prediction/notebook)
