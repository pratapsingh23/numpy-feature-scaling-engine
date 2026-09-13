# NumPy Preprocessing Math Engine 

A scratch implementation of fundamental Feature Scaling algorithms using NumPy vectorized operations.

## Features Implemented 
- **Min-Max Normalization **: Scales data range into `[0, 1]`.
- **Z-Score Standardization **: Rescales data to have `Mean = 0` and `Std Dev = 1`.
- **Column-wise Vectorization **: Utilizes `axis=0` for efficient processing without explicit loops.

## Why Scale Features? 
Machine Learning models (e.g., KNN, Linear Regression, SVM) rely on distance metrics. Features with larger numerical ranges (e.g., House Prices) can dominate features with smaller ranges (e.g., Age). Scaling brings all features to an equal standing.
