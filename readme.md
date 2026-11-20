# Titanic Passenger Survival — Pandas EDA

An exploratory data analysis of the Kaggle Titanic training dataset using Python and Pandas only.

The analysis inspects the dataset, handles missing values, examines passenger survival rates, and saves a cleaned CSV file.

## Dataset

Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)

The training data is located at `data/raw/train.csv`.

## Analysis

The notebook covers:

- Dataset shape and structure
- Summary statistics
- Missing values and duplicate records
- Missing age and embarkation port handling
- Removal of the Cabin column
- Overall survival rate
- Survival rates by sex, passenger class, embarkation port, and age group
- Correlations between numerical variables
- Export of cleaned data to `data/processed/titanic_cleaned.csv`

## Key Results

- 342 of 891 passengers survived (38.38%).
- Female passengers had a 74.20% survival rate, compared with 18.89% for male passengers.
- First-class passengers had the highest survival rate at 62.96%, followed by second class at 47.28% and third class at 24.24%.
- Survival rates were 55.36% at Cherbourg, 38.96% at Queenstown, and 33.90% at Southampton.
- Children had the highest survival rate among the age groups at 57.97%.

## Project Structure

```text
Titanic_EDA_In_Python/
├── data/
│   ├── raw/
│   │   └── train.csv
│   └── processed/
│       └── titanic_cleaned.csv
├── notebooks/
│   └── Titanic_EDA_Pandas.ipynb
└── readme.md
```

## Setup

Create and activate a virtual environment:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

Install the required packages:

```powershell
python -m pip install pandas jupyter
```

Open `notebooks/Titanic_EDA_Pandas.ipynb` in Jupyter or VS Code and run the cells from top to bottom.

## Limitations

Missing ages were replaced with the median age, and missing embarkation ports were replaced with the most common port. The Cabin column was removed because it contains many missing values. The analysis describes patterns in the training data and does not establish causation.

## Author

Muhammad Abdullah
