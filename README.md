# AI-Based Construction Delay Prediction & Risk Analytics

## Overview
A machine-learning project that predicts whether a construction activity is likely to be delayed based on operational and project-related factors.

> **Data disclaimer:** The included dataset is synthetic and was generated for demonstration/learning purposes. It is not real company or project data.

## Business Problem
Construction delays can cause cost overruns, resource under-utilization and disruption to downstream activities. This project demonstrates an early-warning approach that helps project teams identify high-risk activities before delays occur.

## Features
- Material availability
- Labour availability
- Equipment availability
- Vendor performance
- Weather severity
- Activity complexity
- Planned duration
- Previous delays
- Change orders
- Activity type

## Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier

## Evaluation
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook construction_delay_prediction.ipynb
```

Open the notebook and run all cells.

## Project Structure

```text
construction-delay-prediction/
│
├── construction_delay_prediction.ipynb
├── construction_data.csv
├── README.md
└── requirements.txt
```

## Business Application
A high predicted delay probability can trigger preventive actions such as:
- expediting materials,
- reallocating labour,
- escalating poor vendor performance,
- resequencing dependent activities,
- increasing supervision for complex activities.

## Future Enhancements
- Integrate real project schedule/ERP data
- Add cost-overrun prediction
- Create a Power BI/Tableau dashboard
- Add SHAP-based explainability
- Deploy as a Streamlit application

## Author
Add your name here before publishing.
