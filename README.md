## Gold Price Prediction Project

This project focuses on building a machine learning model to predict the price of gold (GLD) based on related financial indicators.

**Steps performed:**

1.  **Data Collection and Processing:** Loaded the gold price data from a CSV file and performed initial data exploration, including checking the shape, information, missing values, and descriptive statistics of the dataset.
2.  **Correlation Analysis:** Visualized the correlations between different financial indicators and the gold price using a heatmap to understand the relationships.
3.  **Feature and Target Splitting:** Separated the features (SPX, USO, SLV, EUR/USD) and the target variable (GLD price) for model training.
4.  **Data Splitting:** Divided the data into training and testing sets to evaluate the model's performance on unseen data.
5.  **Model Training:** Trained a Random Forest Regressor model on the training data.
6.  **Model Evaluation:** Evaluated the trained model using appropriate regression metrics:
    *   R-squared error to assess the goodness of fit.
    *   Mean Absolute Error (MAE) to measure the average prediction error.
    *   Mean Squared Error (MSE) to measure the average squared prediction error.
7.  **Visualization:** Plotted the actual gold prices against the predicted gold prices to visually compare the model's performance.

This project demonstrates a basic workflow for building and evaluating a regression model for financial time series data.

