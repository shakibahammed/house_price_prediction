
House Price Affordability Prediction (Machine Learning Project)

Overview
  This project aims to predict house price affordability using machine learning techniques. It analyzes real-world housing data and builds a regression model to estimate the Price-to-Income Ratio.

 Objectives
   Predict housing affordability based on economic indicators
   Apply feature engineering to improve model performance
   Compare multiple machine learning models
    Build an interactive interface for real-time prediction



 Machine Learning Workflow

1.Data Preprocessing
  Handled missing values using median imputation
  Removed non-numeric features (e.g., City column)

2.Exploratory Data Analysis (EDA)
  Scatter plots, histograms, and boxplots
  Correlation heatmap to identify relationships

3.Feature Engineering
   Log transformation (`log1p`)
   Polynomial features (squared features)
   Created additional features to capture non-linear patterns

4.Model Training
  Random Forest Regressor
  Gradient Boosting Regressor
 
5.Model Evaluation
    R² Score
    Mean Absolute Error (MAE)



Results
   Achieved strong prediction performance using ensemble models
   Random Forest performed best on validation and test data
   Feature importance analysis helped identify key factors affecting affordability



Interactive Prediction System
 Built using Python `ipywidgets`
 Users can input:
    Affordability Index
    Rent Yield (City & Outside)
    Price-to-Rent Ratio
    Mortgage Percentage
 System returns:
    Predicted affordability score
    Classification (Affordable / Expensive)


Technologies Used
   Python
   Pandas, NumPy
   Scikit-learn
   Matplotlib, Seaborn
   ipywidgets


Future Improvements
    Deploy as a web application (Flask / Streamlit)
    Hyperparameter tuning (GridSearchCV)
    Cross-validation for robust evaluation



Author
Md. Shakib Ahammed  
BSc in Computer Science & Engineering  
