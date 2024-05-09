# Linear_Regression_Assignment-Final

This programming assignment tasks with building a multiple linear regression model aimed at predicting the demand for shared bikes.

**Problem Statement:**
BoomBikes, a prominent US bike-sharing provider, has faced significant revenue declines amidst the ongoing COVID-19 pandemic. To navigate these challenging times and prepare for a post-lockdown resurgence, BoomBikes is eager to gain insights into the demand for shared bikes once normalcy returns. The objective is to devise a robust business plan that accelerates revenue growth by accurately anticipating consumer demand and tailoring their services accordingly.

**Goal:**
The primary objective is to model the demand for shared bikes using available independent variables. This predictive model will serve as a crucial tool for management to understand the dynamics of demand and tailor business strategies accordingly. By leveraging insights from the model, BoomBikes aims to optimize resource allocation, enhance customer satisfaction, and position itself as a market leader in the post-pandemic era.

**Data:**
The dataset provided contains various independent variables that may influence bike demand, such as weather conditions, seasonality, and societal trends. However, certain variables, such as 'weathersit' and 'season', are encoded numerically but do not possess inherent order. As such, it is imperative to convert these numeric values into categorical string values to prevent any misconceptions during model building. Additionally, while the 'yr' column may seem simplistic with only two values (0 and 1), indicating the years 2018 and 2019, respectively, its inclusion in the analysis is crucial. Despite its apparent simplicity, 'yr' reflects the increasing popularity and demand for bike-sharing systems over time.

**Model Building:**
The model aims to predict the total number of bike rentals ('cnt') based on various independent variables. Notably, the dataset includes three columns—'casual', 'registered', and 'cnt'. While 'casual' represents the number of casual users who made a rental and 'registered' indicates the total number of registered users who made a booking on a given day, 'cnt' encapsulates the overall bike rentals, including both casual and registered users. Hence, 'cnt' serves as the target variable for model building.

**Model Evaluation:**
After constructing the regression model and conducting residual analysis, the evaluation phase involves assessing the model's performance on a test dataset. Specifically, the R-squared score on the test set provides a quantitative measure of the model's predictive accuracy, offering valuable insights into its effectiveness in forecasting bike demand.

**Documents Included:**
The following have been included in the assignment:
1. A well commented Jupyter file: **Linear_Regression_Assignment_Final.ipynb**
2. An assignment question file: **Linear Regression Assignment Questions.pdf**
