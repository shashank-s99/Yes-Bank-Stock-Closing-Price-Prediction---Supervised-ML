# Yes-Bank-Stock-Closing-Price-Prediction---Supervised-ML

![yes_bank3](https://github.com/user-attachments/assets/6d056d5a-3d7f-423a-9d61-6e84fcd32f2b)



This repository contains the code and documentation for the project on predicting Yes Bank's stock closing prices using supervised machine learning techniques, specifically Lasso Regression with GridSearchCV.

**Introduction**

The goal of this project is to develop a predictive model to forecast the closing prices of Yes Bank stocks. This involves data preprocessing, feature engineering, model training, and evaluation. The model aims to assist traders and investors by providing insights into future stock price movements.

**Dataset**

The dataset used in this project includes historical stock prices of Yes Bank. The data contains columns such as Date, Open, High, Low, Close, Volume, and other relevant financial indicators.

**Methodology**

**Data Preprocessing:**

- Handling missing values.
- Normalizing/standardizing data.
- Creating new features based on existing ones (e.g., moving averages).

**Feature Engineering:**

- Extracting relevant features from the raw data.
- Performing correlation analysis to select significant features.

**Model Training:**

- Splitting the data into training and testing sets.
- Implementing Lasso Regression with GridSearchCV for hyperparameter tuning.

**Model Evaluation:**

- Evaluating the model using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² score.
- Visualizing the model's performance through plots.

**Results**

**Model Performance:**

- R² Score: 0.8974
- RMSE: 5.32
- MAE: (to be filled based on the notebook output)

**Visualizations:**

- Plot of actual vs. predicted closing prices.

**Conclusion**

The Lasso Regression model with GridSearchCV has shown promising results in predicting Yes Bank's stock closing prices. The model's high R² score and low RMSE indicate good predictive power, making it a useful tool for investors.

**Future Work**

- Explore additional features to further improve model accuracy.
- Experiment with other machine learning algorithms such as Random Forest, XGBoost, and Neural Networks.
- Incorporate more recent data to keep the model up-to-date.
