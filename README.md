
## Danone Hackathon - neural network

### Steps:

- One-Hot Encoding for categorical variables
- Distribution analysis and removing outliers
- Splitting to train, validation and test
- Standard Scaler for normalizing data
- Converting to tensors PyTorch
- We build and train a model (MLP), define an optimizer and a loss function
- Analyze training indicators and save the model

## Kaggle Competition - ML model

We need to forecast the number of good which will be sold in each shop next month.

Link https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview

### Steps:

- Data preprocessing and adding features
- Adding lag features (since time-series data)
- Splitting to test, validation, train
- Build and test models:
     - Logistic regression
     - XGBoost with cross-validation to select the best hyper-parameters
- Compare the accuracy of the models:
     - RMSE, Logistic regression = 1.25
     - RMSE, XGBoost = 1.23
