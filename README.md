# House-Price-Prediction

This project predicts house prices using the Kaggle dataset with a Gradient Boosting Regressor. Utilizing Pandas for data handling, NumPy for numerical operations, and Scikit-learn for model training and evaluation, the model is optimized for accuracy. 

# Project Overview

This project aims to predict house prices using a dataset from Kaggle. The dataset includes various features related to house attributes. By employing a Gradient Boosting Regressor, the project explores advanced regression techniques to create a predictive model. The process involves data preprocessing, feature engineering, and model evaluation to ensure accurate and reliable price predictions. The trained model is then saved using Joblib for ease of deployment and future use.

# Key Features

- **Data Collection and Processing**: 
  - Utilizes the [Kaggle House Prices dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) containing various features like lot area, year built, garage, etc.
  - Includes comprehensive data preprocessing such as handling missing values, encoding categorical variables, and feature scaling.

- **Data Handling**: 
  - Employs Pandas for data manipulation and NumPy for numerical operations.
  - Splits the dataset into training and testing sets to ensure robust model validation.

- **Regression Model**: 
  - Implements Gradient Boosting Regressor, enhanced through hyperparameter tuning to optimize model performance.
  
- **Model Evaluation**: 
  - Assesses model performance using cross-validation techniques to ensure reliability.
  - Achieves an R² score of 0.891, indicating a high level of accuracy in predicting house prices.

- **Model Persistence**: 
  - Saves the trained model with Joblib, allowing for easy deployment and reuse in future predictions.

## Conclusion

The house price prediction model demonstrates the effectiveness of Gradient Boosting Regressor in capturing complex patterns within the Kaggle dataset. With rigorous data preprocessing and a robust evaluation process, the model achieves an impressive R² score of 0.891, reflecting its high accuracy. By saving the trained model with Joblib, this project ensures that the predictions can be utilized for future analysis. Overall, this model provides a reliable tool for estimating house prices based on a variety of features.

---
