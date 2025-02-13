# Real Estate Prediction Using Machine Learning  

## Overview  
This project focuses on processing and analyzing real estate data to predict a specific outcome variable (OutcomeVariable). Several regression models and machine learning techniques were implemented to enhance prediction accuracy.  

## Workflow  
1. Data cleaning and exploratory analysis.  
2. Applying various regression models (Linear, Ridge, Lasso).  
3. Using Grid Search to optimize models.  
4. Comparing model performance based on the R1 Score.  

## Results  
The models were evaluated using the R1 Score, and the results are as follows:  
| Model                  | R1 Score |  
|------------------------|----------|  
| Linear Regression      | 0.885163 |  
| Ridge Regression       | 0.889012 |  
| Lasso Regression       | 0.895931 |  
| Lasso Grid Search      | 0.900422 |  
| Ridge Grid Search      | 0.879213 |  
| Random Forest          | 0.893875 |  
| Gradient Boosting      | 0.890650 |  

## How to Use the Project  
1. Load and preprocess the dataset as outlined in the code.  
2. Run the provided script to experiment with models and evaluate performance.  
3. Modify parameters or add new models to improve the results.  

## Requirements  
- Python 3.8+  
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn  

## Contribution  
Contributions are welcome to improve the project or add new techniques. Please open an issue or submit a pull request.  
