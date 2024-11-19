# **Dynamic Flight Fare Prediction**

## **Overview**
The **Dynamic Flight Fare Prediction** project analyzes and predicts flight ticket prices using advanced machine learning techniques. Flight prices are influenced by factors such as demand, seasonality, and booking timelines, leading to dynamic pricing patterns. This project employs data science methodologies to model these changes and forecast prices effectively. 

The project involves thorough data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning model implementation to ensure accurate predictions. It uses a robust dataset to uncover critical patterns and build models capable of delivering reliable forecasts for both regression and classification tasks.

## **Key Features**
- **Data Preprocessing**:
  - Addressed missing values, encoded categorical variables, and scaled numerical features.
  - Managed a large dataset (47 MB Excel file) efficiently for modeling purposes.
- **Exploratory Data Analysis (EDA)**:
  - Analyzed fare trends across airlines, routes, and booking timelines.
  - Visualized critical factors influencing flight prices using Python libraries like matplotlib and seaborn.
- **Machine Learning Models**:
  - **Regression Models**: XGBoost, Random Forest, and Gradient Boosting for fare prediction.
  - **Classification Models**: XGBoost, Random Forest, and Gradient Boosting for fare categorization (e.g., low, medium, high).
  - Evaluated model performance using R², RMSE, and AUC metrics.

## **Tools and Technologies**
- **Programming Language**: Python  
- **Libraries Used**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost  
- **Environment**: Jupyter Notebook for model development  
- **Version Control**: GitHub  

## **Project Results**
### **Regression Performance**
- **XGBoost Regressor**:
  - RMSE: 0.1628
  - R²: 0.9551
- **Random Forest Regressor**:
  - RMSE: 0.1934
  - R²: 0.9367
- **Gradient Boosting Regressor**:
  - RMSE: 0.1642
  - R²: 0.9543

### **Classification Performance**
- **XGBoost Classifier**:
  - AUC: 0.9882
- **Random Forest Classifier**:
  - AUC: 0.9754
- **Gradient Boosting Classifier**:
  - AUC: 0.9868

The regression models demonstrated high accuracy in predicting dynamic flight prices, with XGBoost performing the best in both regression and classification tasks. The classification task provided a clear categorization of fares into low, medium, and high brackets, with XGBoost achieving the highest AUC score.

## **Conclusion**
This project successfully leveraged data science and machine learning to predict flight prices and categorize fare levels with high accuracy. By addressing challenges in preprocessing, feature engineering, and modeling, the work demonstrates the value of data-driven decision-making in dynamic pricing scenarios. The project results provide a strong foundation for applying similar methodologies in other dynamic pricing contexts.
