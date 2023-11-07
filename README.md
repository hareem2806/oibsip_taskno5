# oibsip_taskno5

Linear Regression for Sales Prediction


Overview:
This repository contains a Python script for performing linear regression to predict sales based on advertising expenses in TV, radio, and newspapers. The project covers various stages, including data exploration, preprocessing, and the development of a predictive model. Below are the key sections of this project:

Reading File:
The script reads data from a CSV file named 'Advertising.csv' and loads it into a Pandas DataFrame for analysis.

Exploring DataSet:
The dataset is explored through various steps, including displaying the first and last rows, checking its shape, obtaining information about the data types, and summarizing its statistics.

Checking for Inconsistent Data:
This section deals with data inconsistencies, addressing duplication, null or missing values, renaming inconsistent column names, and checking data types for consistency.

Exploratory Data Analysis (EDA):
EDA is performed to visualize data distributions and examine the relationships between advertising expenses (TV, radio, and newspaper) and sales. This is achieved using histograms and scatter plots to gain insights.

Visualizing Distributions through Histograms:
Histograms are created to visualize the distributions of advertising expenses in TV, radio, and newspapers. These visualizations offer a clear perspective on the data's characteristics.

Visualizing Relationship between Attributes and Sales through Scatter Plots:
Scatter plots are utilized to visualize the relationships between advertising expenses and sales, such as TV ad expenses, radio ad expenses, and newspaper ad expenses in relation to sales.

Visualizing Correlation through Heatmap:
A heatmap is generated to illustrate the correlation between different attributes, helping to identify which factors have the most significant influence on sales.

Splitting Data:
The dataset is divided into training and testing sets, a crucial step for building and evaluating the Linear Regression model.

Linear Regression:
The script utilizes Linear Regression to build a predictive model for sales. It calculates the accuracy of the model, makes predictions, and visualizes actual versus predicted values. Metrics such as R-squared (R2), Mean Absolute Error (MAE), and Mean Squared Error (MSE) are reported to evaluate the model's performance.
