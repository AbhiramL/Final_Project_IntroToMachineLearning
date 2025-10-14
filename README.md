# Final_Project_IntroToMachineLearning
# Telco Customer Churn Prediction

## Overview
This project predicts customer churn using the IBM Telco dataset.  
We explore the data, clean it, and build predictive models (Logistic Regression, Random Forest, SVM).

## Project Structure
- `notebooks/`: Jupyter notebooks for EDA and modeling
- `src/`: helper functions
- `data/`: dataset (excluded from repo if large)

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open .ipynb in `notebooks/` and run cells

## Results
- Logistic Regression ROC-AUC: ~0.82
- Random Forest ROC-AUC: ~0.85
- SVM ROC-AUC: ~0.84

## Next Steps
- Hyperparameter tuning
- Feature importance analysis
- Deployment as a web app
