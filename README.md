# King-County-House-Price-Prediction

## Project Description
This data science project is about predicting house prices based on various features of properties such as square footage, number of rooms, location, etc. in a given dataset. The goal is to estimate a continuous variable — house prices — using using various regression models such as Linear Regression, Ridge Regression, Lasso Regression, Random Forest and XGBoost. To evaluate the performance of the regression models, R-squared and Mean Squared Error (MSE) were chosen as key metrics. R-squared measures the proportion of variance in house prices that is explained by our model, providing insight into its explanatory power. Meanwhile, MSE quantifies the average squared difference between predicted and actual values and helps to assess the accuracy of the predictions. Together, these metrics offer a comprehensive view of how well our model performs in predicting house prices.

## Data Used
- `data/kc_house_data.csv`: The dataset for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data), and is available under the [CC0 License](https://creativecommons.org/publicdomain/zero/1.0/). This dataset contains house sale prices for King County, which includes Seattle. The King County housing data was collected from May 2014 to May 2015.

## Project Steps
1. Exploratory Data Analysis (EDA)
2. Data Preparation
3. Model Training (Linear Regression, Ridge Regression, Lasso Regression, Random Forest, XGBoost)
4. Principal Component Analysis
5. Feature Engineering
6. Model Evaluation and Comparison
7. Final model selection

8. ## Requirements
- **Python 3.x**: The project is developed in Python, so you'll need to have Python 3.x installed.
- **Jupyter Notebooks**: To run the exploratory data analysis (EDA) and other analysis steps, you will need Jupyter Notebooks.
- **NumPy**: Required for numerical operations.
- **pandas**: Required for data manipulation and analysis.
- **Matplotlib**: Required for data visualization.
- **Seaborn**: Required for statistical data visualization.
- **scikit-learn**: Required for machine learning models, data preprocessing, and evaluation metrics.
  - Includes: `ColumnTransformer`, `Pipeline`, `SimpleImputer`, `StandardScaler`, `OneHotEncoder`, `FunctionTransformer`, `train_test_split`, `LinearRegression`, `Ridge`, `Lasso`, `RandomForestRegressor`, `SVR`, `GridSearchCV`, `KFold`, `cross_val_score`, `PCA`, `mean_absolute_error`, `mean_squared_error`, `r2_score`.
- **XGBoost**: Required for the XGBRegressor model.
- **Other Python libraries**: Install all necessary Python libraries by running:
```bash
pip install -r requirements.txt
