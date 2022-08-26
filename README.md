# Optimizing data into clusters by original data vs PCA

This application pulls data from the resource folder and uses unsupervised machine learning to group the data into clusters first by the original data, then by using principal component analysis (PCA) to reduce the dimensions of the data to group into clusters.

---

## Technologies

Using Python 3.7

* [pandas](https://github.com/google/pandas) - For data analysis

* [Scikit-Learn](https://github.com/scikit-learn) - For data analysis KMeans, PCA, and StandardScaler

* [hvplot](https://github.com/holoviz/hvplot) - For plotting both charts and the geographical maps.

---

## Installation Guide

```python
  pip install pandas
  pip install -U scikit-learn
  pip install holoviz
```

---

## Usage

Upload data of crypto's percentage returns for 24hrs, 7 days, 14 days, 30 days, 60 days, 200 days, and 1 year. This data then gets processed using all these input factors to be clustered, then uses PCA to reduce the dimensions to just 3. The code optimizes for the ideal number of clusters then compares using all factors vs the PCA factors.

---

## Contributors

Sole Contributor - Josh Thompkins

---

## License

Everyone is free to view and work with this project, you may not alter text unless given explicit permission.
