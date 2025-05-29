# Sales Prediction Project

This notebook demonstrates a sales prediction project using machine learning models. The goal is to predict sales based on advertising spending on different platforms (TV, Radio, and Newspaper).

## Data

The project uses the `Advertising.csv` dataset, which contains information about advertising budgets and corresponding sales.

## Models Used

The following regression models are trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Results

The notebook compares the performance of these models using Mean Squared Error (MSE) and R-squared (R2) metrics. Feature importance is also analyzed for the Random Forest model.

## Conclusion

Based on the analysis, the Random Forest model identifies TV advertising as the most important factor in predicting sales, followed by Radio. Newspaper advertising has a less significant impact.

## How to Run

1.  Mount your Google Drive in Colab.
2.  Ensure the `Advertising.csv` file is located at `/content/drive/My Drive/Colab Notebooks/Advertising/Advertising.csv`.
3.  Run all cells in the notebook.
