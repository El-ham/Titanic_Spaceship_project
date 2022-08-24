# Titanic_Spaceship_project
This is my submission for getting started kaggle competition "Spaceship Titanic".
Link to the kaggle page: https://www.kaggle.com/competitions/spaceship-titanic
In "Titanic_spaceship_project.ipynb" I first go through data exploration, some visualization, data cleaning and feature engineering which at the end gives me the 'df_clean.csv' file.
Then, I run several Machine learning algorithm, using cross validation and grid search and find xgboost algorithm as the best predictor for this data.
Finally, I do the same data cleaning and feature engineering for the test data ('df_test.csv') and run the trained xgboost algorithm to do the prediction and get the 'sample_submission.csv' file as a result. This submission score is 0.80173 while the best obtaind score for this data is 0.87023 at this time.
These mentioned four files are in the repository.
