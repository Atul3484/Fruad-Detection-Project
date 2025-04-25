# Fruad-Detection-Project
Fruad Detection In Auto Insuarance Claims 

# Fraud Detection Project

This project aims to detect fraudulent insurance claims using machine learning models. The dataset contains insurance claim records with features like customer details, policy information, and incident details.

## Dataset
- **File**: `cleaned_insurance_claims.xlsx`
- **Description**: Contains 990 records with 42 features, including policy details, claim amounts, and fraud labels.
- **Source**: Local file (not included in the repository due to size/privacy).

## Notebook
- **File**: `fraud_detection_final.ipynb`
- **Description**: Jupyter Notebook with data preprocessing, feature engineering, and model evaluation steps.
- **Key Steps**:
  - Data loading and exploration
  - Handling missing values
  - Feature engineering (e.g., days since policy bind, incident day of week)
  - Model accuracy comparison (Logistic Regression, Random Forest, XGBoost)

## Requirements
- Python 3.12
- Libraries: `pandas`, `seaborn`, `matplotlib`
- Install dependencies: `pip install pandas seaborn matplotlib`

## How to Run
1. Place the `cleaned_insurance_claims.xlsx` file in the specified path or update the path in the notebook.
2. Open `fraud_detection_final.ipynb` in Jupyter Notebook.
3. Run the cells sequentially to reproduce the analysis.

## Notes
- The model training code is not fully included in the provided notebook excerpt.
- Ensure the dataset path is correct before running the notebook.


