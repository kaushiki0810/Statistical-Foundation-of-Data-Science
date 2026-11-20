# Practical 10: Principal Component Analysis (PCA)

## Aim
To understand and implement Principal Component Analysis (PCA) using the Wine dataset and reduce the dimensionality of data while retaining maximum possible information.

## Objectives
- To understand the concept and importance of PCA.
- To explore the Wine dataset using descriptive statistics.
- To visualize data using boxplots and scatterplots.
- To calculate and understand the covariance matrix.
- To standardize features using StandardScaler.
- To apply PCA to reduce the dimensions of the dataset.
- To understand principal components and explained variance.
- To visualize different wine classes using principal components.

## Concepts Covered
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Boxplots and Scatterplots
- Covariance Matrix
- Feature Scaling
- StandardScaler
- Principal Component Analysis (PCA)
- Dimensionality Reduction
- Explained Variance Ratio
- 3D Visualization

## Tools and Libraries Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
Wine Dataset (built-in Scikit-learn dataset).

The dataset contains 13 numerical features describing wine samples belonging to three different classes.

## Practical Description
In this practical, Principal Component Analysis (PCA) is implemented using the Wine dataset.

First, descriptive statistics, boxplots, and scatterplots are used to explore the dataset. A covariance matrix is then created to understand relationships between different features.

The features are standardized using StandardScaler before applying PCA. PCA is used to reduce the original 13 features to three principal components.

Finally, a 3D visualization is created to understand the distribution of the three wine classes, and the explained variance ratio is examined.

## How to Run
1. Open the notebook in Google Colab.
2. Run all code cells sequentially.
3. Observe the descriptive statistics and visualizations.
4. Examine the covariance matrix.
5. Observe the scaled feature values.
6. Run PCA and examine the 3D visualization and explained variance ratio.

## Conclusion
This practical helped us understand Principal Component Analysis (PCA) and its importance in dimensionality reduction. We explored the Wine dataset, calculated its covariance matrix, standardized the features, and reduced the original 13 features to three principal components. We also used 3D visualization and explained variance to understand how PCA preserves important information.
