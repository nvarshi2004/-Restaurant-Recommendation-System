# Restaurant Recommendation System

A machine learning-based system to recommend restaurants based on user preferences, cuisine types, and geographic data.

## Features
- Predicts restaurant ratings using XGBoost Regression.
- Recommends restaurants based on user-selected cuisines.
- Classifies cuisine types by region using Random Forest Classifier.
- Interactive location-based visualization using Folium maps.

## Technologies Used
- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, Folium

## Dataset
Restaurant data including:
- Cuisine types
- Ratings
- Latitude & Longitude
- Average cost for two

## How It Works
1. **Data Preprocessing** – Cleaned and encoded the dataset
2. **Model Training** – Trained regression and classification models
3. **Cuisine Filtering** – Filter restaurants based on cuisine choice
4. **Visualization** – Plotted interactive maps to display restaurant clusters
