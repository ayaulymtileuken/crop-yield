# Machine Learning-Based Prediction of Cereal and Legume Crop Yield in Northern Kazakhstan

## Overview

This project develops machine learning models to predict cereal and legume crop yields in Northern Kazakhstan using climatic, environmental, and remote sensing data. The objective is to identify the key environmental factors influencing crop productivity and evaluate the effectiveness of different machine learning algorithms for agricultural yield prediction.

The project integrates satellite-derived vegetation indices, weather variables, soil characteristics, and topographic information into a unified dataset for predictive modeling.

---

## Research Question

**What are the key environmental drivers of cereal and legume crop yield variability in Northern Kazakhstan, and how effectively can machine learning models predict crop yield using climatic and remote sensing data?**

---

## Dataset

The dataset combines agricultural statistics with environmental variables collected from multiple public sources.

### Features

* **Vegetation**

  * Monthly NDVI (May–September)
  * Seasonal mean NDVI

* **Climate**

  * Monthly temperature
  * Monthly precipitation
  * Monthly soil moisture
  * Monthly evapotranspiration
  * Seasonal aggregated variables

* **Topography**

  * Elevation
  * Slope

* **Soil Properties**

  * Soil Organic Carbon (SOC)
  * Soil pH
  * Clay content

### Target Variable

* Crop yield of cereal and legume crops

---

## Study Area

The analysis focuses on districts located in Northern Kazakhstan, including regions such as:

* Akmola
* Kostanay
* North Kazakhstan
* Pavlodar

---

## Methodology

The project follows a complete machine learning workflow:

1. Data collection from multiple public sources
2. Data cleaning and preprocessing
3. Feature engineering
4. Exploratory Data Analysis (EDA)
5. Correlation analysis
6. Model training
7. Hyperparameter tuning
8. Model evaluation
9. Model comparison

---

## Machine Learning Models

The following regression models were implemented and evaluated:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Random Forest Regressor
* XGBoost Regressor

Hyperparameter optimization was performed where appropriate to improve predictive performance.

---

## Model Evaluation

Models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

The models were compared to identify the most accurate approach for predicting crop yields.

---

## Technologies Used

### Programming Language

* Python

### Libraries

* pandas
* NumPy
* Matplotlib
* scikit-learn
* XGBoost
* Statsmodels
* GeoPandas
