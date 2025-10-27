# Diabetes Prediction
Practical machine learning project that builds a reproducible pipeline to predict diabetes from clinical measurements. Focused on clear preprocessing, modest feature engineering, and robust evaluation.
Achieves **82.9% AUC** and **74.0% accuracy** on the held-out test set (RandomForest with class balancing).

## Overview
This project uses the Pima Indians Diabetes Database and a RandomForest classifier with class balancing to improve detection of diabetes cases. The pipeline ingests raw clinical features (e.g., glucose, BMI, age), handles missing values, and produces trained models ready for basic evaluation or demonstration.
Key improvements include simple, explainable feature transforms, careful train/test handling to avoid leakage, and tuning via cross-validation.
## Quick Start
```bash
git clone https://github.com/ngocdangnguyenn/diabetes-prediction.git
cd diabetes-prediction
pip install -r requirements.txt
jupyter notebook notebooks/
```

## Project Structure
```
├── data/
│   ├── raw/diabetes.csv           
│   └── processed/                 
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_model_training.ipynb
├── models/final_model.pkl         
└── requirements.txt
```

## Contact
- Email: nndnguyen2016@gmail.com
- LinkedIn: https://www.linkedin.com/in/ngocdangnguyenn
- Portfolio: https://ngocdangnguyenn.github.io/portfolio/ 