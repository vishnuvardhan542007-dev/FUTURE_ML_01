# Sales Forecasting using Machine Learning

## Project Overview
This project predicts retail sales using historical sales data and machine learning techniques. The workflow includes data preprocessing, feature engineering, model training, evaluation, and sales prediction.

## Dataset
The project uses the following datasets:
- train.csv
- test.csv
- stores.csv
- transactions.csv
- oil.csv
- holidays_events.csv

> **Note:** The `train.csv` file is excluded from this repository because it exceeds GitHub's file size limit.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Model
- Random Forest Regressor

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Project Structure

```
FUTURE_ML_01/
│
├── data/
├── notebooks/
│   └── Sales_Forecasting.ipynb
├── images/
├── models/
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

```bash
git clone <repository-url>
cd FUTURE_ML_01

pip install -r requirements.txt

jupyter notebook
```

Open:

```
notebooks/Sales_Forecasting.ipynb
```

and run all cells.

## Results
The model forecasts future sales using historical retail data and engineered features. It demonstrates the complete machine learning workflow from preprocessing to prediction.

## Author
**Vishnu Vardhan**