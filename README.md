# Titanic Survival Prediction

A machine learning classification project that predicts whether a passenger survived the Titanic disaster using passenger information such as age, sex, passenger class, fare, and family relationships.

## Project Overview

The objective is to build and evaluate machine learning models for predicting Titanic passenger survival.

This project follows an end-to-end machine learning workflow, including exploratory data analysis, data preprocessing, feature engineering, model training, evaluation, and Kaggle submission.

## Dataset

The dataset comes from the [Kaggle Titanic: Machine Learning from Disaster competition](https://www.kaggle.com/competitions/titanic).

- Training data: 891 passengers
- Test data: 418 passengers
- Target variable: `Survived`
  - `0`: Did not survive
  - `1`: Survived

## Project Structure

```text
Titanic-Survival-Prediction/
├── data/
│   └── raw/
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   └── 02_full_workflow.ipynb
├── outputs/
│   └── titanic_submission.csv
├── .gitignore
└── README.md
```

## Machine Learning Workflow

1. Exploratory Data Analysis (EDA)
2. Missing-value analysis and preprocessing
3. Feature engineering:
   - FamilySize
   - IsAlone
   - Title
4. Numerical feature scaling
5. Categorical feature encoding
6. Model training:
   - Logistic Regression
   - Random Forest
7. Hyperparameter tuning using GridSearchCV
8. Model evaluation and comparison
9. Kaggle test predictions and submission

## Models and Results

| Model | Validation Accuracy |
|---|---:|
| Logistic Regression | 84.36% |
| Random Forest | To be recorded |
| Tuned Random Forest | To be recorded |

**Kaggle public leaderboard score:** 0.78229

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Kaggle

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/roshanregmiml/Titanic-Survival-Prediction.git
```

2. Navigate to the project directory:

```bash
cd Titanic-Survival-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the notebooks in order:
   - `01_exploratory_data_analysis.ipynb`
   - `02_full_workflow.ipynb`

## Author

**Roshan Regmi**

GitHub: [@roshanregmiml](https://github.com/roshanregmiml)

## Project Status

Completed initial machine learning workflow and Kaggle submission. Further improvements in feature engineering, model optimization, and evaluation are planned.