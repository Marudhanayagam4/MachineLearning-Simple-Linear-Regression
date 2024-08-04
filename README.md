# HR Salary Prediction Model

This project builds a linear regression model to predict salaries based on years of experience. The model is trained on a dataset of salaries and saved for future predictions.

## Project Structure

- `Salary_Data.csv`: The dataset containing years of experience and corresponding salaries.
- `salary_prediction.py`: The main script to train, evaluate, save, and load the model.
- `finalized_model.sav`: The serialized trained model.

## Requirements

- pandas
- scikit-learn
- pickle

Install the required libraries using:
```bash
pip install pandas scikit-learn

## Description
The script performs the following steps:

✔ Loads the dataset.
✔ Splits the data into training and testing sets.
✔ Trains a linear regression model.
✔ Evaluates the model using the R-squared score.


Saves the trained model using pickle.
Loads the saved model and predicts salary based on user input.
