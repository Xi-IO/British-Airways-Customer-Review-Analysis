# British Airways Customer Behavior Analysis

## Project Overview
This project simulates a real-world data analysis pipeline aimed at understanding customer behavior and predicting booking completion for an airline, using web-scraped review data from the Skytrax website.

The goal is to extract actionable insights for improving customer satisfaction and optimizing sales strategies through data-driven analysis and machine learning modeling.

## Workflow Summary
1. **Data Extraction**: Scraped customer reviews using BeautifulSoup to simulate real-world data collection challenges.
2. **Data Cleaning**: Handled missing values, encoded categorical variables, and prepared features for modeling.
3. **Exploratory Data Analysis (EDA)**: Visualized data distributions and identified potential patterns.
4. **Predictive Modeling**:
   - Built a Random Forest classifier with cross-validation and threshold tuning.
   - Built an XGBoost classifier with SMOTE oversampling and feature importance analysis.
   - Evaluated models using precision, recall, F1 score, and cross-validation accuracy.
5. **Model Interpretability**:
   - Applied SHAP (SHapley Additive exPlanations) to explain feature contributions and enhance model transparency.

## Key Results
- Identified key factors influencing booking completion, such as origin, stay length, baggage purchases, and online sales channels.
- Achieved balanced precision and recall through custom threshold adjustment.
- Visualized top contributing features using SHAP values for interpretability.

## Technologies Used
- Python (pandas, numpy, scikit-learn, xgboost, imbalanced-learn)
- Data visualization (matplotlib, seaborn)
- Model interpretation (SHAP)
- Web scraping (BeautifulSoup)

## Repository Structure
- `Getting_Started.ipynb` — Full end-to-end project notebook
- `README.md` — Project documentation

## Acknowledgments
This project was developed as a learning exercise to simulate real-world data science workflows for customer behavior analysis.
