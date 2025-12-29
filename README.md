# Expert-System-for-Mask-Hyginene
Pattern Recognition Project Winter2025-26


# Compliance Log Analysis

This repository contains the code and notebook for an ML-based analysis of a compliance event log (`compliance_log.csv`). The goal is to explore the data, build and evaluate a predictive model, and report results in a reproducible way.[web:20]

## Project Overview

The project:
- Loads and cleans the compliance log data from `compliance_log.csv`.
- Performs exploratory data analysis (EDA) on key variables and targets.
- Trains and evaluates one or more ML models to predict the target outcome.
- Produces figures and tables that are exported into `Figures_Tables/` for the final report and Teams submission.[web:20]

## Dataset: `compliance_log.csv`

- Source: Provided by the course as the main dataset for the project.[web:9]
- Format: A comma-separated file where each row is a logged compliance-related event or case.[web:8]
- Usage: The notebook loads `compliance_log.csv` from the repository root (or a `data/` subfolder, depending on how you organize files) and uses it for all analyses and model training.[web:11]

Update this section with:
- The exact path you chose for `compliance_log.csv` (e.g. `./compliance_log.csv` or `./data/compliance_log.csv`).
- A short description of the most important columns (ID, timestamp, features, target label).

## Model Description

The main notebook (`main_mask_sys.ipynb`) builds and evaluates the ML model.[web:18]

You should briefly describe here:
- Model type (e.g. **logistic** regression, **random** forest, gradient boosting, etc.).
- Input features (which columns from `compliance_log.csv` are used, and how they are preprocessed, e.g. scaling, encoding, handling missing values).
- Target variable (what is being predicted, e.g. compliance violation vs. non-violation).
- Evaluation metrics (e.g. accuracy, precision, recall, F1, ROC-AUC) and how model performance is compared.[web:18]

Example text (adapt to your case):

> The baseline model is a logistic regression trained on engineered features derived from event counts, categorical encodings, and time-based attributes. The target is a binary label indicating whether a case results in a compliance breach. Model performance is evaluated using train–test splits and metrics such as F1-score and ROC-AUC.

## How to Run the Notebook

1. **Clone the repository**
git clone https://github.com/mxtu-devp9/Expert-System-for-Mask-Hygiene.git
cd main_mask_sys

#Create and activate env

Use conda, venv 

#Install dependencies

install the main packages you used (e.g. `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `jupyter`)

4. **Place the dataset**

Make sure `compliance_log.csv` is in the expected location (e.g. repository root or `data/` folder) so that the notebook’s data-loading cell runs without changes.

5. **Launch Jupyter and run the notebook**

Open Mask_System.ipynb and run with 'restart kernel and run all cells'


#Submitting files 

1. ipynb notebook
2. git repo url
3. figures_tables.zip
