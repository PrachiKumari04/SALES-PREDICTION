Sales Prediction

Overview -
This project uses machine learning to predict the sales of a company based on various features such as advertising expenditure, seasonality, and economic indicators. The goal is to analyze historical sales data and develop a model that accurately estimates future sales.

Dataset -
The dataset used is the Advertising Sales Dataset, which contains information on sales, advertising expenditure, seasonality, and economic indicators.

Features
- Advertising Expenditure: The amount spent on advertising
- Seasonality: The time of year (e.g., summer, winter)
- Economic Indicators: GDP, inflation rate, unemployment rate
- Sales: The sales of the company

Preprocessing
- Handling missing values: Missing values in the dataset are handled using appropriate methods (e.g., mean, median, imputation)
- Encoding categorical variables: Categorical variables (e.g., seasonality) are encoded using LabelEncoder
- Scaling/normalizing numerical variables: Numerical variables (e.g., advertising expenditure, economic indicators) are scaled/normalized using StandardScaler

Feature Engineering
- Advertising Expenditure: The advertising expenditure feature is transformed into a numerical representation using TF-IDF
- Seasonality: The seasonality feature is encoded using LabelEncoder
- Economic Indicators: The economic indicators features are scaled/normalized using StandardScaler

Model Selection
- Linear Regression: A linear regression model is trained on the preprocessed data to predict sales
- Decision Tree Regressor: A decision tree regressor model is trained on the preprocessed data to predict sales
- Random Forest Regressor: A random forest regressor model is trained on the preprocessed data to predict sales

Evaluation
- Mean Squared Error (MSE): The MSE is calculated to evaluate the performance of the models
- R-squared: The R-squared value is calculated to evaluate the goodness of fit of the models
- Mean Absolute Error (MAE): The MAE is calculated to evaluate the performance of the models

Visualization
- Distribution of Sales: The distribution of sales is visualized using a histogram
- Predicted vs. Actual Sales: The predicted sales are plotted against the actual sales using a scatter plot
- Residuals: The residuals are visualized using a histogram
- Feature Importance: The feature importance is visualized using a bar plot

Prediction
- New Data: New data is defined with its features (advertising expenditure, seasonality, economic indicators)
- Prediction: The sales are predicted using the trained model

Requirements
- Python: 3.8+
- Pandas: 1.3+
- NumPy: 1.21+
- Matplotlib: 3.4+
- Seaborn: 0.11+
- Scikit-learn: 1.0+

Author
Prachi Kumari (prachikumari2804@gmail.com)
