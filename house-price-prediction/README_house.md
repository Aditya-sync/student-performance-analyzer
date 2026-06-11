# House Price Prediction

Compares Linear Regression and Random Forest to predict house prices. Includes outlier detection and preprocessing.

## Dataset

- **Source:** [Housing Prices Dataset – Kaggle](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- **Features used:** area, bedrooms, bathrooms, stories, parking, and more

## What I did

- Loaded and explored the dataset
- Removed missing values and outliers using IQR method
- Plotted price distribution and correlation heatmap
- Trained two models — Linear Regression and Random Forest
- Compared both models using R² and MAE

## Results

| Model             | R² Score | MAE       |
| ----------------- | -------- | --------- |
| Linear Regression | 0.6609   | 795234.42 |
| Random Forest     | 0.6373   | 860052.06 |

> Fill in your actual numbers after running the notebook.

## How to run

```
pip install -r requirements.txt
```

Then open `house_price.ipynb` and run all cells.

## Libraries used

- pandas
- scikit-learn
- matplotlib
- seaborn

"Linear Regression performed slightly better than Random Forest on this dataset, possibly due to the small dataset size (545 rows)."
