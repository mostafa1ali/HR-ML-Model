# HR Salary Prediction

This project is a machine learning pipeline for predicting employee salaries based on HR data. It includes data exploration, visualization, preprocessing, feature engineering, model training, and evaluation using linear regression.

## Dataset

- The dataset is loaded from `Human resources.csv`.
- It contains various features such as `PerfScoreID`, `EngagementSurvey`, `EmpSatisfaction`, `SpecialProjectsCount`, `DaysLateLast30`, `Absences`, and the target variable `Salary`.

## Project Structure

- Data loading and exploration
- Visualization of important features
- Feature engineering (e.g., creating `Annual_Salary`)
- Data preprocessing (imputation, scaling, encoding)
- Model training using `LinearRegression`
- Model evaluation (RMSE, R2 Score)

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Place `Human resources.csv` in the project directory.
2. Open and run the notebook `HR.ipynb` step by step.
3. The notebook will output data visualizations, model performance metrics, and predictions.

## Model Evaluation

- The model is evaluated using RMSE and R2 Score on both training and validation sets.
- Example output:
  ```
  RMSE for training set using LinearRegression -- 0.000
  RMSE for validating set using LinearRegression -- 0.000
  R2 Score for training set using LinearRegression -- 1.000
  R2 Score for validating set using LinearRegression -- 1.000
  ```

## License

This project is for educational purposes.