# Spotify Popularity Prediction

This repository is composed of two datasets, a jupyter notebook and a README.

Both datasets have informations concerning songs uploaded on the platform Spotify : name, danceability, loudness etc.
- The first dataset shows popularity using a boolean. 
- The second dataset uses a scale from 0 to 100 to convey popularity.

In the Notebook, we'll use each dataset to work with regression and classification models to try and predict songs' popularity.

## Summary

**Regression:**

- Data analysis & cleanup
- Label Encoder
- Standard Scaler
- Finding the best Regressor
- Grid Search on Random Forest models

**Classification:**

- Data analysis & cleanup
- Label Encoder
- Standard Scaler
- Finding the best Classifier
- Logistic Regression model

___

The **data** used in this notebook was downloaded here :
- classification : https://www.kaggle.com/datasets/akiboy96/spotify-dataset
- regression : https://www.kaggle.com/datasets/faisalsalar/spotify-songs-of-pop-and-its-sub-genres