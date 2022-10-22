## EXPLORATORY DATA ANALYSIS ON NYC TAXI TRIP DURATION ##

This project deals with the exploratory data analysis on [NYC-taxi-trip-duration-dataset](https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data) taken from Kaggle.

The EDA process is done in the following steps:

1. **Preprocessing the data** - This step involved the checking for the missing values and the presence of outliers.\
The distance was calculated from the latitude-longitude columns and a new feature speed was extracted from the distance\
and time columns. All the variables were encoded to numerical with dummy encoding.

2. **Univariate analysis** - This step goes deep into the searching for any inconsistency in the single columns and\
the necessary remedies are taken.

3. **Binvariate analysis** - This helps in finding the relationship between variable and helps in finding outliers and\
significant columns in our dataset.

4. **Correlation heatmap** - This step helps in identifying overall trends and can be helpful for Dimensionality reduction\
like factor analysis or PCA.
