# Titanic Data Preprocessing  
Preprocessing the Kaggle Titanic dataset for ML models.

## Overview  
This project cleans and prepares the Titanic dataset by handling missing values and removing irrelevant features.

## Tools  
- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib (for visualization)  

## Steps  
1. Loaded and explored the dataset.  
2. Visualized survival rates by class.  
3. Filled missing `Age` with median, dropped `Cabin`, and cleaned `Embarked`.  
4. Removed unnecessary columns (`PassengerId`, `Name`, `Ticket`).  

## Files  
- `titanic_preprocessing.ipynb`: Full preprocessing code.  

## How to Run  
1. Install dependencies: `pip install pandas numpy seaborn matplotlib`  
2. Download the dataset from [Kaggle Titanic](https://www.kaggle.com/c/titanic/data).  
3. Run the notebook: `jupyter notebook titanic_preprocessing.ipynb`  