# Student Performance Analyzer

Predicts a student's math score using Linear Regression based on their background and other exam scores.

## Dataset

- **Source:** [Students Performance in Exams – Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Rows:** 1000
- **Features used:** gender, race/ethnicity, parental education, lunch type, test preparation, reading score, writing score

## What I did

- Loaded and explored the dataset
- Plotted score distributions and a correlation heatmap
- Encoded categorical columns using LabelEncoder
- Split data into 80% train / 20% test
- Trained a Linear Regression model to predict math score
- Evaluated using R² Score and MAE

## Results

| Metric | Score |
|---|---|
| R² Score | 0.87 |
| Mean Absolute Error | 4.1 |


## How to run

```
pip install -r requirements.txt
```

Then open `student_analysis.ipynb` and run all cells.

## Libraries used

- pandas
- scikit-learn
- matplotlib
- seaborn
