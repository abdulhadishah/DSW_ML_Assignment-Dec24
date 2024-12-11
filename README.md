# DSW_ML_Assignment-Dec24

This repository contains code and data related to the DSW Machine Learning assignment for December 2024. It includes an exploratory data analysis (EDA) and models built using Logistic Regression and Random Forest for predictive analytics.

## Project Structure

```
DSW_ML_Assignment-Dec24/
│
├── Session 1/                 # Contains EDA notebook
│   └── eda.ipynb              # Jupyter notebook for exploratory data analysis
│
├── Session 2/                 # Contains model training and prediction script
│   └── model__py.py           # Python script for model training and evaluation
│
├── final_model.pkl            # Final trained model (combined or selected model)
├── logistic_regression_model.pkl  # Logistic Regression model file
├── random_forest_model.pkl    # Random Forest model file
├── cleaned_train_data.csv     # Cleaned training dataset
├── test_data.xlsx             # Excel file with test data
├── train_data.xlsx            # Excel file with original training data
```

## Description

- **EDA (Exploratory Data Analysis)**: The `eda.ipynb` file contains detailed analysis of the training data, including data cleaning, visualization, and feature exploration.
  
- **Model Training**: The `model__py.py` script trains two machine learning models:
  - **Logistic Regression**
  - **Random Forest**
  
  Both models are then evaluated on test data.

- **Model Files**: 
  - `logistic_regression_model.pkl` and `random_forest_model.pkl` are saved models, which can be used for predictions.
  - `final_model.pkl` is the final model after combining or selecting the best model.

- **Data Files**: 
  - `cleaned_train_data.csv` is the preprocessed training data used for model training.
  - `test_data.xlsx` and `train_data.xlsx` contain the original and test datasets used in the analysis.

## Getting Started

### Prerequisites

Install the necessary libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

### Running the Code

1. **Load the EDA Notebook**:
   - Open `eda.ipynb` in a Jupyter Notebook or Google Colab environment to explore the data and perform analysis.

2. **Run the Model Training Script**:
   - Open `model__py.py` in a Python environment.
   - Ensure that `train_data.xlsx` and `test_data.xlsx` are in the same directory as the script or update the file paths accordingly.
   - The script will load the training data, train both Logistic Regression and Random Forest models, and output the performance metrics.

3. **Make Predictions**:
   - Use the trained models (`logistic_regression_model.pkl`, `random_forest_model.pkl`) to make predictions on new data.
