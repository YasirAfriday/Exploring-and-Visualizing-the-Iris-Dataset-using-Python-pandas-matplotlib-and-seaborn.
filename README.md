# Exploring & Visualizing the Iris Dataset

An in-depth exploratory data analysis (EDA) and visualization of the classic **Iris flower dataset**, using Python with **pandas**, **matplotlib**, and **seaborn**.

## About the dataset

The Iris dataset, introduced by Ronald A. Fisher in 1936, contains 150 records of iris flowers. Each record has four numeric features and one target label:

| Feature | Description |
|---|---|
| `sepal_length` | Sepal length in cm |
| `sepal_width`  | Sepal width in cm |
| `petal_length` | Petal length in cm |
| `petal_width`  | Petal width in cm |
| `species` (target) | One of: *setosa*, *versicolor*, *virginica* |

## What's in this repo

- [`iris-eda-analysis.pdf`](iris-eda-analysis.pdf) — A 3-page PDF export of the Colab notebook walking through the EDA: data loading, summary statistics, distribution plots, pair plots, and per-species comparisons.

## Tools used

- Python 3
- pandas — data loading and summary
- matplotlib — base plotting
- seaborn — statistical visualization (pair plots, KDE, box plots)

## How to reproduce

```bash
pip install pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Then load the Iris dataset from `sklearn.datasets.load_iris()` or seaborn's `sns.load_dataset("iris")` and follow along with the analysis steps shown in the PDF.

## Author

[YasirAfriday](https://github.com/YasirAfriday)
