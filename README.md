# Titanic Data Analytics Project

## Overview
Analysis and cleaning of the Titanic dataset, focusing on handling missing data and basic visualisation.

## Steps
1. Download train.csv from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data).
2. Run the Python script to:
   - Identify and handle missing values
   - Perform exploratory visualisation
   - Save cleaned dataset



| Data Dictionary       | Variable	Definition                             | Key                                 |
|-----------------------|--------------------------------------------------|-------------------------------------|
| survival              | Survival                                         | 0 = No, 1 = Yes                     |
| pclass                | Ticket Class                                     | 1 = 1st, 2 = 2nd, 3 = 3rd           |
| sex                   | Gender                                           |                                     |
| Age                   | Age in years                                     |                                     |
| sibsp                 | # of siblings / spouses aboard the Titanic       |                                     |
| parch                 | # of parents / children aboard the Titanic       |                                     |
| ticket                | Ticket Number                                    |                                     |
| fare                  | Passenger fare	                                 |                                     |
| cabin                 | Cabin number                                     |                                     |
| embarked              | Port of Embarkation                              | C = Cherbourg, Q = Queenstown, S = Southampton                            |




## Methods
- Dropped "Cabin" (mostly missing)
- Imputed "Age" with median (numeric)
- Imputed "Embarked" with mode (categorical)

## Requirements
- pandas, numpy, matplotlib, seaborn, missingno

## Structure
```plaintext
Titanic/
├── train.csv 
├── Titanic.ipnyb
├── README.md
└── Titanic_cleaned.csv
```
<!--the folder structure was still displaying as plain text, so used a fenced code block with language identifier for better formatting.
This tells the renderer that the block is plain text --> 

## Contact
For questions or feedback, contact: Vish | https://github.com/vipai/
