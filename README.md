# dataScienceCapstoneProject
## Capstone Project: Create a Customer Segmentation Report for Arvato Financial Services
## Data Science Udacity Nanodegree Project

### Introduction:
In this project, I will analyze demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. The aim of this project is to create a predictio model that predicts which individuals are most likely to convert into becoming customers for the Bertelsmann Arvato company.

1. Get to Know the Data
Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. In this part, data is going to be cleaned (handle missing, incomplete, missleading data) and analyzed through visualizations to have a better understanding of what algorithms and features are appropriate for solving the problem.

2. Customer Segmentation Report
Here, an unsupervised learning techniques is going to describe the relationship between the demographics of the company's existing customers and the general population of Germany. It is going to be described which parts of the general population are more likely to be part of the mail-order company's main customer base, and which parts of the general population are less so.
 
3. Supervised Learning Model
Here, prediction model is going to be built. The output at the end should use the demographic information from each individual to decide whether or not it will be worth it to include that person in the campaign.

4. Kaggle Competition
Created model that predicts which individuals are most likely to respond to a mailout campaign, is going to be tested in kaggle competition. This part prepares data to fit into kaggles competition format.

5. Documentation
Medium blog to document all of the steps from start to finish can be found here: https://olga-haberny.medium.com/customer-segmentation-report-for-arvato-financial-services-727e9980ee10

### Instructions:
Please run cells in jupyter-notebook "Arvato Project Workbook_own.ipynb" in order to see the results.

### Project components:
- README.md - this readme file
- Arvato Project Workbook_own.ipynb - jupyter-notebook file that consists main work
- licence files - in /terms_and_conditions folder
- data files - in /data folder, all used files, saved locally

### Software and libraries:
The project uses Python3.
Used libraries:
- numpy
- pandas
- pickle
- project_tests
- matplotlib 
- seaborn
- sklearn

### Data:

- Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

All data is provided by partners at Bertelsmann Arvato Analytics and is their property.

### Results:
All results are provided in Arvato Project Workbook_own.ipynb and documented in Medium blog.

