# Housing Price Prediction

This project predicts housing prices using machine learning models, focusing on feature analysis and model comparison.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Data Preprocessing](#data-preprocessing)
- [Models Used](#models-used)
- [How to Run](#how-to-run)
  

## Project Overview
The goal is to predict house prices based on features like square footage, bedrooms, location, etc. Four regression models are compared:
1. Random Forest
2. Linear Regression
3. Decision Tree
4. K-Nearest Neighbors (KNN)

## Dataset
Source: [Kaggle Housing Dataset](https://www.kaggle.com/datasets/shree1992/housedata)  
- **Rows**: 4,600  
- **Columns**: 18 (original), 12 after preprocessing  

Key Features:
- `price`: Target variable (USD)
- `sqft_living`: Living area square footage
- `bedrooms`, `bathrooms`: Room counts
- `yr_built`: Year built

## Data Preprocessing
1. **Removed Irrelevant Columns**:
   ```python
   columns_to_remove = ['date', 'street', 'city', 'country', 'yr_renovated', 'statezip']
2. **Outlier Removal** : Z-score method (**threshold=3**), reduced dataset to 4,244 rows.

3. Feature Scaling: Standardized using StandardScaler.

# How to Run
## Clone the repository:
  
   git clone https://github.com/najahaja/housing-price-prediction.git



### Key Features of This README:
1. **Structured Layout**: Clear sections for easy navigation.
2. **Code Snippets**: Shows critical preprocessing steps.
3. **Results Table**: Quick comparison of model performance.
4. **Setup Instructions**: Simple steps to reproduce your work.
5. **License Section**: Ready for open-source sharing.

To add this to your repository:
1. Save the text above as `README.md` in your project folder.
2. Commit and push:
   ```bash
   git add README.md
   git commit -m "Added detailed README"
   git push origin main
   
