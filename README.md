# Iris Species Data Exploration

### Overview

This project demonstrates data exploration techniques using the Iris dataset. The dataset contains information about the Iris flower species, specifically the physical measurements of the flowers and their species classification. The goal of this project is to load the data, visualize the distribution of species, and understand the relationships between various features through scatter plots and histograms.

### Objectives

The key objectives of this project are:

- Data Loading: Import and inspect the Iris dataset.
- Data Exploration: Understand the distribution of features and identify patterns.
- Data Visualization:
    - Create scatter plots to observe relationships between features.
    - Generate histograms to visualize feature distributions.
    - Analyze species-wise trends in the dataset.

### Quality Issues

Checked for:
- Missing values (none found).
- Outliers in measurements (e.g., extreme petal/sepal lengths).

Cleaning:
- Standardize numerical features for consistency.
- Encode species labels numerically.

### Dataset

The Iris dataset was introduced by R.A. Fisher in 1936 and has become a classic in machine learning and data science. It contains the following columns:

- Id: Unique identifier for each record.
- SepalLengthCm: Length of the sepal in centimeters.
- SepalWidthCm: Width of the sepal in centimeters.
- PetalLengthCm: Length of the petal in centimeters.
- PetalWidthCm: Width of the petal in centimeters.
- Species: The species of the Iris flower (e.g., Iris-setosa, Iris-versicolor, Iris-virginica).

This dataset contains 150 samples with 50 samples from each of the three Iris species.

### Data Visualization

- Pairplot: A pairplot was created to visualize the relationships between different feature pairs (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm), with species differentiation.
- Histograms: Histograms of the individual features (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm) were plotted to observe their distribution.
- Boxplots: Boxplots were used to check for any outliers in the features and visualize the range of values for each feature.
- Scatterplots: Scatterplots were used to visualize the relationships between the sepal and petal measurements, with color-coding to differentiate the species.

##### Boxplot checks for outliers in the features

![screenshot-github com-2025 01 27-12_28_37](https://github.com/user-attachments/assets/8a08ea50-eb59-4df3-9325-2055a36f8c09)

### Results

Feature Relationships:
- Scatter plots reveal strong linear relationships between petal length and petal width.
- Sepal measurements show more overlap across species compared to petal measurements.

Species Distribution:
- Each species has distinct patterns in feature measurements, making it easier to classify.

### Next Steps

Once we have cleaned the data and understood the relationships between features we can proceed with building machine learning models (e.g Logistic, KNN, or Random Forest for classification) to predict the species of the iris flowers.

### Source

https://www.kaggle.com/datasets/uciml/iris
