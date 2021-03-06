# Data Scientist Nanodegree Capstone Project
## Customer Segmentation Report for Arvato Financial Services

Follow this [link](https://chris-b.medium.com/customer-segmentation-report-for-arvato-financial-services-79f09ec1e02c) to read a post about this project on Medium.

### Table of Contents

1. [Project Overview](#overview)
2. [Installation](#installation)
2. [Dataset](#dataset)
3. [Scope](#scope)
3. [Results](#results)
4. [Licensing and Acknowledgements](#licensing)


## Project Overview<a name="overview"></a>
The analyze of demographics data for customers of a mail-order sales company in Germany is in focus, comparing it against demographics information for the general population. There will be used unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. Then, with the information of a third dataset with demographics information for targets of a marketing campaign for the company is used to predict which individuals are most likely to convert into becoming customers for the company. The used data has been provided by Bertelsmann Arvato Analytics, and represents a real-life data science task.

The project is divided into following subtasks:
1.	Part 0: Get to Know the Data;
2.	Part 1: Customer Segmentation Report;
3.	Part 2: Supervised Learning Model
4.	Part 3: Kaggle Competition;

## Installation <a name="installation"></a>
- Python 3.*
- Python libraries: NumPy, Pandas, Scikit-learn, matplotlib, seaborn

## Dataset <a name="dataset"></a>
All the data is provided by Bertelsmann Arvato:
* `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
* `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
* `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
* `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
Additionally, there were 2 more files for describing attributes:
* `DIAS Attributes - Values 2017.xlsx`: Is a detailed mapping of data values for each feature in alphabetical order.
* `DIAS Information Levels - Attributes 2017.xlsx`: Is a top-level list of attributes and descriptions, organized by informational category.

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood.


## Scope <a name="scope"></a>
- README.md
- Arvato Project Workbook.html: HTML version of the project
- Arvato Project Workbook.ipynb: jupyter notebook


## Results <a name="results"></a>
Following concepts implemented and covered in detail in the notebook or blogpost: 
#### Get to Know the Data
#### Data Cleaning
* Missing Values
* Differences between Azdias & Customers
* Replacing unknown Values with NaN
* Re-encode Features
* Impute NaN & Scale the Data
#### Customer Segmentation Report
* The PCA Method
* The Elbow Method
* Kmeans Clustering
* Deep Dive in most affected Cluster
#### Supervised Learning Model
* Starting point
* Selection of the best model
* Hypertuning of the selected model
#### Summary and potential for improvement


## Licensing and Acknowledgements<a name="licensing"></a>
Data belongs to the Bertelsmann Arvato Analytics and Udacity.
