# Business Intelligence & Analytics Projects

This repository contains Business Intelligence and Analytics work developed using **Power BI** and **Python**, covering data modeling, reporting, and predictive analytics.

---

## Project Structure

```text
├── MachineLearning.pbix
├── titanic-cf.ipynb
│
├── data/
│
├── images/
│
└── README.md
```

---

## 1. Machine Learning – Titanic Survival Prediction

**Notebook:** `titanic-cf.ipynb`

A complete machine learning workflow implemented in Python to predict passenger survival in the Titanic dataset.

### Work performed
- Exploratory data analysis and data cleaning.
- Feature engineering (age groups, family size, travel status).
- Encoding of categorical variables.
- Training and evaluation of classification models.
- Hyperparameter tuning and model comparison.
- Generation of prediction outputs for Kaggle submission.

### Notebook Overview
![Titanic Notebook](images/TitanicKaggleNotebook.png)

---

## 2. Machine Learning Results Reporting

**File:** `MachineLearning.pbix`

A Power BI report developed to analyse and visualise the machine learning predictions.

### Work performed
- Imported processed datasets and prediction results.
- Built visuals comparing predicted survival versus actual survival.
- Analysed survival patterns by:
  - Gender
  - Age group
  - Passenger class
  - Embarkation port
  - Travel status (alone vs not alone)
- Added interactive filtering by passenger class.

### Survival Analysis

**Factors Influencing Survival**  
![Survival Factors](images/FactorsSurvival.png)

**Model vs Actual Survival Comparison**  
![Survival Model Comparison](images/FactorsSurvivalModel.png)

---

## Tools & Technologies
- Power BI Desktop  
- Python (Jupyter Notebook)  
- pandas, numpy, scikit-learn, matplotlib, seaborn

---

## Author
Cristiana Fonseca