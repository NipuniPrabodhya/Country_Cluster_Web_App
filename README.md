# Country Cluster Web App

A machine learning web application that uses the K-Means clustering algorithm to group countries based on their geographical coordinates.

## Project Overview

This project applies K-Means clustering to country longitude and latitude data. The model groups countries into geographical clusters based on similarities in their locations.

The project was developed from a Data Science and Analytics lab exercise involving feature selection, data standardization, K-Means clustering, cluster visualization, and the Elbow Method for identifying an appropriate number of clusters.

## Machine Learning Approach

The model uses:

* Longitude
* Latitude
* StandardScaler
* K-Means Clustering
* WCSS
* Elbow Method

The geographical features are standardized before applying K-Means because differences in variable ranges can affect Euclidean distance calculations.

## Dataset

The project uses `Countries.csv`, which contains geographical information for 241 countries.

Main columns:

* Country Name
* Longitude
* Latitude

## Project Structure

```text
Country Cluster Web App/
├── data/
│   └── Countries.csv
├── notebooks/
│   └── country_clustering_kmeans.ipynb
├── models/
├── src/
├── images/
├── .gitignore
├── README.md
└── requirements.txt
```

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Streamlit
* Joblib

## Current Progress

* [x] Dataset preparation
* [x] Data visualization
* [x] Feature selection
* [x] Feature standardization
* [x] K-Means clustering
* [x] Elbow Method
* [x] Cluster visualization
* [ ] Save trained model
* [ ] Build Streamlit web application
* [ ] Add interactive country/coordinate prediction
* [ ] Complete application testing

## Planned Web Application

The web application will allow users to enter geographical coordinates and determine which geographical cluster those coordinates belong to using the trained K-Means model.

## Note

The clusters represent geographical grouping based only on longitude and latitude. They should not be interpreted as economic, political, cultural, or development-based classifications.
