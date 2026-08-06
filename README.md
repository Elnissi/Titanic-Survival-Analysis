# 🚢 Titanic Survival Analysis

## Overview
This project performs an end-to-end exploratory data analysis (EDA) on the Titanic passenger dataset to understand what factors influenced a passenger's likelihood of survival. Through data cleaning, statistical analysis, and visualisation, the project uncovers how gender, passenger class, age, fare, and embarkation port each played a role in determining who survived the disaster.

## Objectives
- Identify the key factors that influenced survival on the Titanic
- Analyse survival rates across gender, passenger class, age group, and embarkation port
- Handle missing data appropriately and document cleaning decisions
- Produce clear, readable visualisations that communicate findings effectively

## Dataset
The dataset contains **891 passenger records** with 15 features sourced from the Seaborn built-in Titanic dataset (originally from Kaggle).

| Feature | Description |
|---|---|
| `survived` | Target variable: 1 = Survived, 0 = Did not survive |
| `pclass` | Passenger class (1 = First, 2 = Second, 3 = Third) |
| `sex` | Gender of the passenger |
| `age` | Age in years |
| `sibsp` | Number of siblings/spouses aboard |
| `parch` | Number of parents/children aboard |
| `fare` | Ticket fare (£) |
| `embarked` | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

## Tools & Libraries
- **Python 3.x**
- **Pandas** — data loading, cleaning, and manipulation
- **NumPy** — numerical operations and array handling
- **Seaborn** — statistical visualisations
- **Matplotlib** — custom chart styling and layout

## How to Run

```bash
# Clone the repository
git clone https://github.com/elnissiwilliams/titanic-survival-analysis.git
cd titanic-survival-analysis

# Install dependencies
pip install pandas numpy seaborn matplotlib

# Open the notebook
jupyter notebook Titanic_Survival_Analysis.ipynb
```

## Project Structure
```
titanic-survival-analysis/
├── Titanic_Survival_Analysis.ipynb   # Main analysis notebook
└── README.md
```

## Analysis Sections
| # | Section |
|---|---|
| 1 | Load & Inspect the Data |
| 2 | Missing Value Analysis |
| 3 | Data Cleaning |
| 4 | Survival Overview |
| 5 | Survival by Gender |
| 6 | Survival by Passenger Class |
| 7 | Age Distribution & Age Group Breakdown |
| 8 | Fare Analysis |
| 9 | Embarkation Port Analysis |
| 10 | Correlation Heatmap |
| 11 | Class × Gender Combined Analysis |
| 12 | Key Findings & Conclusion |

## Key Findings

| Factor | Finding |
|---|---|
| **Overall survival rate** | 38.4% of passengers survived |
| **Gender** | Female survival rate (~74%) was far higher than male (~19%) |
| **Passenger class** | 1st class: ~63% · 2nd class: ~47% · 3rd class: ~24% |
| **Age** | Children (0–12) had the highest survival rate among all age groups |
| **Fare** | Survivors paid on average ~2× more than non-survivors |
| **Strongest predictor** | Passenger class is the single strongest numerical predictor of survival |
| **Class × Gender** | 1st class females: ~97% survival · 3rd class males: ~16% survival |

## Conclusion
The Titanic disaster was not random — survival was strongly shaped by socioeconomic status, gender, and age. The "women and children first" evacuation protocol is clearly visible in the data, as is the structural advantage held by first-class passengers who had better lifeboat access and cabin locations. This project demonstrates how Python-based EDA can extract meaningful, human insights from historical data.

## Author
**Elnissi Williams**
Data Analyst | Python · SQL · Power BI · Tableau
📧 elnissiwilly04@gmail.com
📁 [GitHub Portfolio](https://github.com/elnissiwilliams)
