
# Customer Behavior Project

###  Overview

This project explores customer transactional data from an online retail store to perform end-to-end data mining and knowledge discovery. The workflow covers:

* Exploratory Data Analysis (EDA)
* Feature engineering
* Customer segmentation using RFM analysis and clustering
* Classification to predict customer segments
* Regression to predict customer monetary value

---

###  Dataset

We used the **Online Retail dataset** from the UCI Machine Learning Repository:

> D. Chen. "Online Retail," UCI Machine Learning Repository, 2015.
> \[Online]. Available: [https://doi.org/10.24432/C5BW33](https://doi.org/10.24432/C5BW33)

The dataset contains transactional data between 2010 and 2011 for a UK-based non-store online retailer.

---

###  Main Steps

1. **EDA and Cleaning**

   * Handle cancellations, missing values, and outliers
   * Explore distributions of quantity, unit price, and spend

2. **Feature Engineering**

   * RFM metrics: Recency, Frequency, Monetary
   * Derived metrics: AvgBasketSize, AvgOrderValue, MonetaryPerItem
   * Time-based features (day of week, time of day)

3. **Clustering**

   * KMeans and Agglomerative clustering


4. **Classification**

   * Predict customer clusters using Random Forest and Logistic Regression


5. **Regression**

   * Predict monetary spend using Random Forest and Linear Regression

---

###  Tools Used

* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* Jupyter Notebook

---

