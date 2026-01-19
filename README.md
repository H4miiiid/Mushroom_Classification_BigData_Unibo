# Mushroom Classification — Big Data (UNIBO)

This repository contains my Big Data course project for classifying mushrooms (edible vs. poisonous) using the **Secondary Mushroom Dataset**. The work includes data preprocessing, exploratory analysis, model training, hyperparameter tuning, and evaluation.

## Repository Structure
Mushroom_Classification_BigData_Unibo/
├── Dataset/
│ └── secondary_data.csv
└── Notebooks/
├── Big_Data_CourseProject_Mushroom_Classification.ipynb
└── Big_Data_ProjectWork_Mushroom_Classification.ipynb

## Dataset
- Path: `Dataset/secondary_data.csv`
- CSV delimiter: `;`

## Notebooks
- `Notebooks/Big_Data_CourseProject_Mushroom_Classification.ipynb`  
  Main course project notebook (EDA, preprocessing, modeling, evaluation).

- `Notebooks/Big_Data_ProjectWork_Mushroom_Classification.ipynb`  
  Additional experiments (model comparisons and hyperparameter tuning).

## How to Run
### Option 1: Run locally
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook
Open a notebook from the Notebooks/ folder and run all cells.

### Option 2: Run on Google Colab

Upload the repository (or the Notebooks/ and Dataset/ folders) to Colab and run the notebooks.
Make sure the dataset remains at: Dataset/secondary_data.csv.
