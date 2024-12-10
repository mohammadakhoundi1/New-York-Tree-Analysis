# DataPreprocessing
This repository contains a robust data preprocessing system designed to address common challenges such as missing values, outliers, inconsistent formatting, and noise. The objective of this project is to enhance the quality, reliability

### Data Exploration

The first step in data preprocessing is to explore the data. This involves listing down the unique values in each feature and finding their lengths. Statistical analysis is performed.


### Data Cleaning

Data cleaning is an essential step in data preprocessing. In this project, missing and inappropriate values are identified and treated appropriately. Duplicate rows are removed, and outliers are identified.

Specifically, the following actions are taken during data cleaning:

- The Nan values in the "problems" column is replaced with None.
- The Nan values in the "health" column is replaced with Good.
- The Nan values in the "spc_latin" column is replaced with No Observation.
- The Nan values in the "sidewalk" column is replaced with No Damage.
- The Nan values in the "steward" column is replaced with No Observation.

### Data Normalization
Normalizing 'tree_dbh' parameter by replacing it's values that are less than 25% or above 75% 

### Data Analysis  
Data analysis is performed to gain insights from the preprocessed data.

### Data Visualization
![image](https://github.com/user-attachments/assets/8c7ed515-9657-4dcc-afc9-f04e4766c85f)
![image](https://github.com/user-attachments/assets/90422cee-21e3-4de8-a156-9f30186b26ca)

## Dataset

find the data here: https://data.cityofnewyork.us/Environ...
