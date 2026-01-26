# Mushroom Classification — Big Data (UNIBO)

This repository contains my Big Data course project for classifying mushrooms (edible vs. poisonous) using the **Secondary Mushroom Dataset**. The notebooks are implemented using **PySpark / Spark ML (MLlib)** and include data preprocessing, exploratory analysis, model training, hyperparameter tuning, and evaluation.

## Repository Structure
```text
Mushroom_Classification_BigData_Unibo/
├── Dataset/
│   └── secondary_data.csv
└── Notebooks/
    ├── Big_Data_CourseProject_Mushroom_Classification_PySpark.ipynb
    └── Big_Data_ProjectWork_Mushroom_Classification_PySpark.ipynb

```

## Dataset
- Path: `Dataset/secondary_data.csv`
- CSV delimiter: `;`

## Notebooks
- `Notebooks/Big_Data_CourseProject_Mushroom_Classification_PySpark.ipynb`  
    Spark ML workflow with tree-based models (Decision Tree, Random Forest, Gradient-Boosted Trees).

- `Notebooks/Big_Data_ProjectWork_Mushroom_Classification_PySpark.ipynb`  
  Spark ML workflow with linear/probabilistic models (Binomial Logistic Regression, Linear SVM, Naive Bayes).

## How to Run
### Option 1: Run locally
Requirements (minimum):
```bash
pip install pyspark numpy matplotlib seaborn jupyter
```
Run: 
```bash
jupyter notebook
```

### Option 2: Run on Google Colab

Upload the repository (or the Notebooks/ and Dataset/ folders) to Colab and run the notebooks.
Make sure the dataset remains at: Dataset/secondary_data.csv.
