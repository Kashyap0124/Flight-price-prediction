✈️ Flight Price Prediction Using Machine Learning

🔍 Project Summary:
I recently completed a data science project focused on predicting flight ticket prices using machine learning techniques. The primary objective was to build a robust regression model that could accurately estimate airfares based on key features such as airline, source, destination, number of stops, duration, and time of travel.

📊 Key Highlights:
Dataset: The dataset consisted of thousands of domestic flight records, including variables like departure/arrival times, total duration, airline type, number of stops, and price.

🧹 Data Preprocessing:
* Converted date/time columns into meaningful features (e.g., day, month, hour).
* Cleaned and encoded categorical variables such as airline, source, and destination using Label Encoding.
* Handled missing values and transformed the duration column for consistency.
* Scaled features appropriately for algorithms like SVR and KNN.

🤖 Models Implemented:
I trained and evaluated multiple regression algorithms:
* Linear Regression
* Ridge & Lasso Regression
* ElasticNet
* Decision Tree Regressor
* Random Forest Regressor
* K-Nearest Neighbors (KNN)
* Support Vector Regressor (SVR)
* XGBoost Regressor

✅ Model Evaluation
* Used RMSE and R² Score as evaluation metrics
* Performed cross-validation to ensure generalizability of the models

📈 Best Performing Model
✅ XGBoost Regressor
* RMSE: ~1563
* R² Score: ~0.88

This model outperformed others in terms of both accuracy and consistency during cross-validation.

🎯 Added Functionality: Recommendation System
Developed a simple rule-based recommendation system that suggests airlines based on user-selected features (like source, destination, number of stops) and predicted performance scores. This helps users choose the best airline based on historical pricing and service quality.

