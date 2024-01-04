
## Danone Hackathon - Neural Network

The task is to predict future sales during the unstable Covid-19 period.

### Steps:

- One-Hot Encoding for categorical variables
- Distribution analysis and removing outliers
- Splitting to train, validation and test
- Standard Scaler for normalizing data
- Converting to tensors PyTorch
- We build and train a model (MLP), define an optimizer and a loss function
- Analyze training indicators and save the model

## Kaggle Competition - Logistic regression & XGBoost

The task is to forecast the number of goods which will be sold in each shop next month.

### Steps:

- Data preprocessing and adding features
- Adding lag features (since time-series data)
- Splitting to train, validation and test
- Build and test models:
     - Logistic regression
     - XGBoost with cross-validation to select the best hyper-parameters
- Compare the accuracy of the models:
     - RMSE, Logistic regression = 1.25
     - RMSE, XGBoost = 1.23
