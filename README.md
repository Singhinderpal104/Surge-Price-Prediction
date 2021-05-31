# Surge-Price-Prediction

## Introduction
     The cab platforms adjust their prices using a specific algorithm which is real time and dynamic known as “Surge Pricing” or “Dynamic Pricing”. This algorithm automatically   raises the price of a trip when the demand increases more than the supply. The surge algorithm generally outputs a multiplier which is adjusted along with the base fare, the price per mile and the price per minute to generate the final price. This price is communicated to the riders and the ride is initiated when they confirm to the price shown. This surge multiplier is kept discrete and may range from 1.2 to the maximum allowed by the government based on geography.
## Workflow:
    This project is divided into 3 parts after importing the basic libraires and reading the dataset.
  ### 1. Pre processing:
     
   **a. EDA**
   - Checked for null values and duplicates.
   - Explored all the coulmns to get visualizations.
      
   **b. Feature Engineering**
   - Used One Hot Encoding to encode the categorical variables.
      
   **c. Data Cleaning**
   - Treated the outliers.
   - Imputed the missing values.
      
   **d. Feature Selection**
   - Used f-regression, chi2 and Extra Trees Classifier for feature selection.
   - Dropped the columns which did not impact the model building much.
    
   ### 2. Model Building:
            
   **a. Fitting different models and tuning hyperparameters**
   - Tried different models like Logistic Regression,Support Vector Machine,  Random Forest, XGBoost Classifier.
   - Used Grid Search CV, Randomised Search CV and Bayseian Search CV for hyperparameter tuning. 
           
   **b. Comparison of Models**
   - Compared the performance of all the built models.
   - Implemented Shap values. 
    
   ### 3. Conclusion
   
## Installation
    The code is written in Python 3.7 using Google Colab Notebook.

     
