# Credit-Risk-Loan-Default-Prediction
Machine learning credit risk prediction pipeline built on AWS to estimate borrower default probability using structured financial features, ensemble models, and explainable AI techniques. Supports scalable model experimentation and quantitative lending risk assessment.


## Project Description
This project develops a machine learning pipeline to estimate borrower default probability using structured financial risk indicators. The solution demonstrates scalable model experimentation, feature engineering, and explainable credit scoring workflows implemented on AWS cloud infrastructure.

## Business Objective
Financial institutions require predictive risk analytics systems to evaluate borrower creditworthiness and reduce loan default exposure. This project aims to build quantitative models that support data-driven lending decisions and portfolio risk monitoring.

## Dataset
- Home Credit Default Risk dataset  
- Structured borrower financial and behavioral attributes  
- Supervised binary classification problem  

## Tech Stack
- Python  
- Machine Learning: Logistic Regression, Random Forest, LightGBM  
- Cloud: Amazon S3, Amazon SageMaker  
- Model Explainability: SHAP  

## Project Workflow
1. Data ingestion and storage in Amazon S3  
2. Exploratory data analysis and preprocessing  
3. Feature engineering for credit risk indicators  
4. Model training and performance comparison  
5. Model explainability using SHAP  
6. Evaluation using ROC-AUC metric  

## Results
- Final Model: Gradient Boosting / LightGBM  
- ROC-AUC Score: 0.79  
- Demonstrates reliable borrower risk classification performance  

## Future Improvements
- Real-time loan approval scoring pipeline  
- Automated model drift monitoring  
- Advanced ensemble modeling strategies  
