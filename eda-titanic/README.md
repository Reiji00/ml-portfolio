# 01 — Titanic: Exploratory Data Analysis

**Phase 1 · Project 1 of 2**

---

## The question

*What factors most strongly predicted survival on the Titanic — and can we find the story in the data before building a single model?*

This project is a deep exploratory analysis of the Titanic passenger dataset. The goal is not prediction — it is understanding. Before any ML model can be meaningful, you have to know your data inside out.

---

## Dataset

**Source:** [Kaggle — Titanic](https://www.kaggle.com/c/titanic/data)
**Size:** 891 rows x 12 columns (training set)

| Column | Description |
|--------|-------------|
| `Survived` | Target — 0 = No, 1 = Yes |
| `Pclass` | Passenger class (1st, 2nd, 3rd) |
| `Sex` | Male / Female |
| `Age` | Age in years (177 missing values) |
| `SibSp` | Siblings/spouses aboard |
| `Parch` | Parents/children aboard |
| `Fare` | Passenger fare |
| `Cabin` | Cabin number (687 missing) |
| `Embarked` | Port of embarkation — C, Q, S |

---

## Key findings

> *(Fill these in as you complete the analysis)*

- **Finding 1:** Women survived at a rate of X% vs Y% for men
- **Finding 2:** First-class passengers were Xx more likely to survive than third-class
- **Finding 3:** Children under 10 had a survival rate of X%

---

## Visualizations

> *(Embed your saved chart images here — save them to figures/ then link below)*

| Survival by class | Survival by sex | Age distribution |
|:-:|:-:|:-:|
| ![class](C:\Users\HP\Desktop\AI-ML\Phase_1\ml-portfolio\eda-titanic\figuressurvival_class_sex.png) | ![sex](figures/survival_by_sex.png) | ![age](figures/age_distribution.png) |

---

## Notebook walkthrough

1. Data loading and first look
2. Missing value audit
3. Univariate analysis — distributions of each feature
4. Bivariate analysis — each feature vs survival
5. Multivariate — interaction effects
6. Key insights in plain English

Open the notebook: [notebook.ipynb](notebook.ipynb)

---

## How to run

```bash
cd 01-eda-titanic
pip install -r requirements.txt
# Download train.csv from Kaggle and place in data/raw/
jupyter notebook notebook.ipynb
```

---

## What I learned

> *(Fill this in when complete)*

- How to systematically audit a dataset for quality issues before analysis
- The difference between missing-at-random vs missing-not-at-random
- How to use Seaborns hue parameter to reveal interaction effects
- Why understanding your data matters more than choosing the right model

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
