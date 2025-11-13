# Titanic Data Analytics Project

## Overview
Analysis and cleaning of the Titanic dataset, focusing on handling missing data and basic visualisation.

## Steps
1. Download train.csv from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data).
2. Run the Python script to:
   - Identify and handle missing values
   - Perform exploratory visualisation
   - Save cleaned dataset

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
Vish
