# -A.P.-Moller-Maersk-DL_ML-Coding-Assessment
# Maersk Supply Chain Sourcing Cost Prediction

This project aims to predict sourcing costs in a supply chain using machine learning models. The dataset used is from Maersk Supply Chain and includes both training and testing datasets.

## Preprocessing

- **Handling Missing Values**: Any missing values in the dataset were addressed.
- **Converting "Month of Sourcing" to Datetime**: The "Month of Sourcing" column was converted to datetime format for easier manipulation.
- **Statistical Summary Printing**: A statistical summary of the dataset was printed to understand the distribution of variables.
- **Label Encoding**: Categorical data was encoded using label encoding to prepare it for modeling.
- **Combining Training and Testing Sets**: The training and testing datasets were combined for preprocessing and modeling.
- **Extracting Month Information**: Month information was extracted from the "Month of Sourcing" column for further analysis.
- **Handling Outliers**: Outliers in the dataset were identified and handled appropriately.

## Exploratory Data Analysis (EDA)

- **Bar Charts**: Bar charts were plotted to visualize the relationship between sourcing cost and product size, product type, and month of sourcing.
- **Top 10 Area Codes**: The top 10 area codes by sourcing cost were analyzed to identify high-cost areas.
- **Maximum Product Size by Area Code**: The maximum product size used in each area code was explored to understand product distribution.

## Machine Learning Models

The following machine learning models were applied to the dataset:

1. **Multiple Linear Regression**
2. **Polynomial Linear Regression**
3. **XGBoost**
4. **Decision Tree**
5. **Random Forest**
6. **KNN Regressor**

## Model Evaluation

The performance of each model was evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R2) Score. The best model was selected based on these scores.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/maersk-supply-chain-sourcing-cost.git

