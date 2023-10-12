# BharathIntern_task-1 House prediction using Linear Regression

Predicting house prices using linear regression is a common machine learning task in the field of real estate and finance. Linear regression is a supervised learning algorithm that models the relationship between a dependent variable (in this case, house prices) and one or more independent variables (features such as the number of bedrooms, square footage, etc.). In this detailed guide, I'll walk you through the steps to build a simple linear regression model to predict house prices.

Project Overview: This project aims to build a machine learning model that predicts house prices based on various features of the houses, such as square footage, number of bedrooms, location, etc. The model uses a linear regression algorithm to make predictions. It's a valuable tool for real estate professionals, homeowners, and anyone interested in estimating house prices.

Prerequisites: Python (3.x) Jupyter Notebook (optional) Libraries: NumPy, Pandas, Scikit-Learn, Matplotlib, etc. Dataset (USA_Housing.csv)

Usage: Data Preparation Download the dataset from the provided Kaggle link and place it in the "data" folder. Open the Jupyter Notebook house_price_prediction.ipynb. Follow the data preprocessing steps mentioned in the notebook, which includes loading the data, handling missing values, and feature engineering.

Training the Model: Train the linear regression model using the prepared data by running the cells in the notebook.

Prediction: Use the trained model to make predictions on new data.

Evaluation: Evaluate the model's performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

Dataset: The dataset used in this project, "USA_HOUSING.csv" contains information about various aspects of houses. It includes features like the number of bedrooms, square footage, location, and more. Refer to the Kaggle dataset page for a detailed description of the features.

Model Architecture: We used a simple linear regression model for this project. The model takes house features as input and predicts the house's sale price as output. No hyperparameter tuning was performed for this example.
