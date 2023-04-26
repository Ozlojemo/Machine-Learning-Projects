# Boston-House Project

## Regression Practice Project

This project aims to build a regression model to predict the prices of houses in Boston. We will use various techniques and algorithms to:

1. Preprocess the data.
2. Detect and handle missing values and outliers.
3. Select features.
4. Train and evaluate the model.


## Libraries Used
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit-learn

### Machine learning project steps

1. Preprocess the data: In this step, we clean and transform the raw data into a format that can be used for machine learning. This might include tasks such as removing duplicates, handling missing values, and converting categorical variables into numerical values. The goal is to create a clean, consistent dataset that accurately represents the problem we want to solve.

2. Detect and handle missing values and outliers: Missing values and outliers can cause problems for machine learning algorithms, so we need to handle them appropriately. Missing values can be imputed (i.e., replaced with estimated values) or removed entirely. Outliers can be identified using statistical techniques and either treated as missing values or removed from the dataset.

3. Select features: Feature selection is the process of choosing which variables to include in our model. We want to select features that are relevant to the problem we are trying to solve, while also avoiding features that are redundant or noisy. There are many techniques for feature selection, including statistical tests, domain knowledge, and machine learning algorithms themselves.

4. Train and evaluate the model: Once we have preprocessed the data and selected features, we can train and evaluate our machine learning model. This involves splitting the data into training and testing sets, choosing an appropriate algorithm, and tuning its hyperparameters. We evaluate the performance of our model using metrics such as accuracy, precision, recall, and F1 score. If the model is not performing well, we may need to revisit the earlier steps to improve the quality of the data or select better features.





## Conclusion
The linear regression model was able to predict the prices of houses in Boston with an R-squared value of 0.812 and a mean squared error (MSE) of 0.025. The polynomial regression model, on the other hand, was able to predict the prices of houses with an R-squared value of 0.813 and an MSE of 0.025. Both models had similar performance, but the polynomial regression model was slightly better
