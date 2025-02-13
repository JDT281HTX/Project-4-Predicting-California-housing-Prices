Project overview 
This project analyzes housing price trends using machine learning models. We apply Linear Regression and Random Forest Regression to predict housing prices based on key features such as median income, location, and housing attributes. The goal is to determine the most influential factors affecting home prices and evaluate the accuracy of predictive models. 

Research Questions 
1. What are the most important factors influencing housing prices?
(Using feature importance analysis from the Random Forest model, we determine which variables contribute the most to housing prices.) 
2. How well can machine learning predict housing prices?
(We evaluate model performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to measure accuracy.)
3. How do the predictions from Linear Regression and Random Forest Regression compare?
(By comparing performance metrics, we assess which model provides the best balance between accuracy and explainability.)

Dataset 
median_house_value (Target Variable)
median_income
housing_median_age
total_rooms, total_bedrooms, households, population
latitude, longitude (Location Data)
ocean_proximity (Categorical) 

Programs used 
Python
Pandas (Data preprocessing)
Matplotlib & Seaborn (Data visualization)
Scikit-Learn (Machine learning models)
Plotly (Interactive visualizations) 

Project Workflow 
1. Data cleaning 
Handled missing values by removing incomplete rows.
Created new derived features (rooms_per_household, bedrooms_per_room, etc.).
Encoded categorical variables (ocean_proximity).
2. Model Training
Split data into training (80%) and testing (20%) sets.
Trained Linear Regression and Random Forest Regression models.
Evaluated models using MAE, MSE, and R² Score.
3. Feature Importance
Identified the most influential features in predicting housing prices.
Median income was found to be the strongest predictor.
4. Data Visualization
Used Matplotlib & Seaborn to visualize model performance.
Created an interactive Plotly scatter plot comparing actual vs. predicted prices.

Results 
The Random Forest model outperformed Linear Regression, achieving higher accuracy and lower error rates.
Median income was the most important factor influencing housing prices, followed by location.
Visualizations effectively highlighted housing trends and model performance.










