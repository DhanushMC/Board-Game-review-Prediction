# Board-Game-review-Prediction

Summary of the Report on Board Game Review Prediction

This project, titled **Board Game Review Prediction**, aims to predict the average ratings of board games using machine learning models. The dataset contains 80,000 board games scraped from BoardGameGeek, with features such as name, playing time, minimum age, user ratings, and average weight.

Key steps in the project:
- Data Preprocessing: Handled missing values, encoded categorical variables, and selected relevant features like 'average_rating' for prediction.
- Data Visualization: Examined correlations between variables to identify key factors affecting board game ratings.
- Model Training: The dataset was trained using two models: Linear Regression and Random Forest Regressor.
- Model Comparison: Random Forest outperformed Linear Regression, with a lower Mean Squared Error (MSE) of 1.47 compared to 2.03.
- Results: The predicted ratings closely matched actual ratings, demonstrating the effectiveness of the Random Forest model.

Conclusion: Random Forest provided better predictions and can help identify factors contributing to board game popularity. Future work includes exploring additional features, experimenting with other machine learning models, and hyperparameter tuning.

Technologies Used: Python, Pandas, Random Forest, Linear Regression, K-Fold Cross Validation.
