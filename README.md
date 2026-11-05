# ML Activity 1: Dataset Preparation (Titanic)

## Activity Description
Prepare a raw dataset for machine learning: inspect it, check data quality, clean it, run basic EDA, encode categorical features, scale numerical features and save the prepared file. No prediction model is built.

## Dataset
- **Titanic dataset**, Kaggle: https://www.kaggle.com/c/titanic/data
- 891 rows x 12 columns, CSV
- Future target: `Survived`

## Work Completed
- Loaded and inspected data (`head`, `tail`, `info`, `describe`)
- Identified numerical and categorical columns
- Checked missing values (count and %), duplicates and category consistency
- EDA: Age histogram, survival by gender, Fare box plot (with observations)
- Dropped `Cabin`, `Name`, `Ticket`; filled `Age` (median) and `Embarked` (mode)
- One-hot encoded `Sex` and `Embarked`
- Standardized `Age` and `Fare` (`PassengerId` not scaled)
- Saved `titanic_prepared.csv`

## Key Results
- Missing: Age 177 (19.87%), Cabin 687 (77.10%), Embarked 2 (0.22%); duplicates: 0
- Females survived far more than males
- Final shape: 891 rows x 10 columns, 0 missing values, 0 duplicates

## Files
- `ML_activity_1.ipynb`: notebook
- `titanic.csv`: raw data
- `titanic_prepared.csv`: prepared data

## Faculty Profile
[Princy Verma on GitHub](https://github.com/Princy2129)

## Acknowledgement
This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: [https://github.com/Princy2129](https://github.com/Princy2129)
