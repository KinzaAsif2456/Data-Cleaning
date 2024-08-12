# Data-Cleaning
This repository contains a collection of scripts, tools, and techniques for cleaning and preprocessing datasets to improve data quality and reliability.
# Data Cleaning Notebook  

## Overview  

This notebook provides a comprehensive guide to data cleaning techniques using Python's Pandas library. It focuses on handling missing data, removing duplicates, and addressing inconsistent values within a dataset, 
This notebooks work on the Titanic dataset

## Contents  

- **Data Overview**: Initial exploration of the dataset, including structure and summary statistics.  
- **Handling Missing Data**: Techniques for filling or dropping missing values.  
- **Duplicate Data**: Methods to identify and remove duplicate entries.  


## Data Cleaning Steps
**1. Data Overview**
The dataset consists of 891 entries with 12 columns, including PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.
Summary statistics and data types are provided for initial insights.
**2. Handling Missing Data**
*Filling Missing Data:*
Used fillna() to replace missing values with constants, preceding values, or mean values.
*Dropping Missing Data:*
Utilized dropna() to remove rows or columns with missing values.
**4. Duplicate Data**
Identified duplicate entries using duplicates().sum().
Removed duplicates with drop_duplicates() to ensure data integrity.
**5. Inconsistent Values**
Addressed data inconsistencies that may arise from data entry errors or collection methods.
Inconsistent Values: Strategies to address data inconsistencies.  


## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
This repository was inspired by the work of [Kinza Asif] and the Google Colab notebook Data Cleaning Notebook.

## Contact
If you have any questions or need help with this repository, please don't hesitate to reach out to [Kinza Asif] at [sweetykinzy2@gmail.com].
