# House Price Prediction using Machine Learning

## About the Project

In this project, I worked on predicting house prices using the House Prices: Advanced Regression Techniques dataset from Kaggle.

My main goal was to understand how different machine learning algorithms perform on a regression problem and how I could improve the predictions through proper preprocessing, model evaluation, and ensemble learning.

Rather than relying on a single model, I experimented with multiple algorithms, compared their performance, and tried combining them to get better results.

## What I Worked On

- Explored the dataset to understand the features and patterns related to house prices.
- Handled missing values in numerical and categorical columns.
- Applied feature scaling and one-hot encoding as part of preprocessing.
- Trained and compared different regression models.
- Used five-fold cross-validation to evaluate model performance.
- Experimented with LightGBM and a weighted ensemble of multiple models.
- Generated predictions and submitted them to the Kaggle competition.

## Models Explored

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net
- Random Forest
- Gradient Boosting
- LightGBM
- Weighted ensemble using `VotingRegressor`

## Results

The best tested cross-validation RMSE was **0.127923**, using a weighted ensemble with a higher weight assigned to LightGBM.

I also recorded a Kaggle leaderboard score of **0.12220** for Version 3.

The cross-validation result and Kaggle score are based on different evaluation data, so they should be interpreted separately.

## Tech Stack

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- LightGBM
- Jupyter Notebook / Kaggle Notebooks

## What I Learned

Through this project, I got more practical experience with the complete machine learning workflow, from exploring and preprocessing data to evaluating models and experimenting with ensemble methods.

It also helped me understand that improving a model is not just about choosing a more complex algorithm. Preprocessing, validation, and understanding how different models perform are equally important.

## Dataset

I used the [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) dataset from Kaggle.

The dataset is not included in this repository. You can download it from the competition page to run the notebook.

## Future Improvements

I would like to explore more feature engineering techniques, experiment with hyperparameter tuning, and investigate other ways to improve model performance.
