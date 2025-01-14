# ML_Project3
Orinson Machine Learning Internship Task 3
**OBJECTIVE**
The objective of this project is to develop a regression model using the California Housing dataset to predict the median house value across different districts in California. This involves exploring and preprocessing the data to ensure quality, training a Random Forest Regressor for accurate predictions, and evaluating its performance using metrics such as MAE, MSE, RMSE, and R-squared. Additionally, the project aims to provide insights into the key factors influencing housing prices through feature importance analysis and visualize the model's performance, demonstrating a comprehensive workflow in machine learning and data science.

**STEP BY STEP EXPLANATION**
Importing Libraries:
The necessary libraries for data manipulation, visualization, and machine learning are imported. These include NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

Loading the Dataset:
The California Housing dataset, which contains housing-related features and target median house values, is loaded and converted into a DataFrame for easier analysis.

Data Exploration:
The first 10 rows of the dataset are displayed to understand its structure, and summary statistics are generated to gain insights into the data distribution. Missing values are also checked to ensure data quality.

Defining Features and Target:
The dataset is split into features (independent variables) and the target (median house value) for further processing.

Splitting Data:
The data is divided into training and testing sets, with 80% used for training the model and 20% reserved for testing.

Feature Scaling:
The features are standardized using a scaler to normalize the data, which improves the performance of many machine learning algorithms.

Model Training:
A Random Forest Regressor is trained using the scaled training data. This ensemble learning method averages predictions from multiple decision trees to improve accuracy and reduce overfitting.

Making Predictions:
The trained model predicts the target values for the test data.

Model Evaluation:
Performance metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²), are calculated to assess how well the model performs.

Visualization of Results:
Two visualizations are created:

A scatter plot compares the true and predicted house values, highlighting the model's accuracy.
A bar chart displays the importance of each feature in influencing the model's predictions.
