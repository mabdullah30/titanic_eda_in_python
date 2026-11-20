# Titanic Passenger Survival - Beginner EDA with Pandas
## Project Overview
This project explores the Kaggle Titanic training dataset using Python and Pandas. It
 inspects the data, checks missing values and duplicates, performs simple cleaning,
 and compares survival rates across passenger groups.
## Tools
- Python
- Pandas
- Jupyter Notebook
- VS Code
## Dataset
Source: https://www.kaggle.com/competitions/titanic
The CSV data is not included in this repository. Download train.csv from Kaggle and
 place it in data/raw/.
## Project Structure
- data/raw/ - original Kaggle files (not committed)
- data/processed/ - cleaned data (not committed)
- notebooks/ - Jupyter notebook
- requirements.txt - Python packages
## Analysis Steps
1. Load and inspect the dataset.
2. Review summary statistics and data types.
3. Identify missing values and duplicates.
4. Fill missing Age and Embarked values and drop Cabin.
5. Compare survival by gender, passenger class, embarkation port, age group, and family
 size.
6. Review fare statistics and a correlation table.
## How to Run
1. Clone this repository.
2. Download train.csv from Kaggle into data/raw/.
3. Create a virtual environment: python -m venv .venv
4. Activate it on Windows PowerShell: .\.venv\Scripts\Activate.ps1
5. Install packages: python -m pip install -r requirements.txt
6. Open the project folder in VS Code.
7. Open notebooks/Titanic_EDA_Beginner_Pandas.ipynb, select the .venv kernel, and run
 cells from top to bottom.
## Key Findings
Complete this section after running the notebook. Include actual percentages and group
 comparisons from your results.
## Limitations
This is a beginner exploratory analysis. Missing Age values are filled using the overall
 median, Cabin is dropped due to extensive missingness, and observed associations do
 not prove causation.
Author: Muhammad Abdullah