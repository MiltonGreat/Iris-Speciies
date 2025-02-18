# Iris Dataset Exploration and Classification

### Overview

This project demonstrates data exploration and classification techniques using the Iris dataset. The dataset provides measurements of Iris flowers, including sepal and petal lengths and widths, along with the species classification. The goal of this project is to explore the dataset through various data visualization techniques, identify relationships between features, clean the data, and lay the foundation for machine learning model development.

### Objectives

The key objectives of this project are:

- Data Exploration: Investigate the distribution of features and species, and uncover patterns in the data.
- Data Visualization:
    - Create scatter plots to examine relationships between features.
    - Generate histograms to visualize feature distributions.
    - Perform boxplot analysis to detect outliers.
- Data Cleaning: Standardize numerical features and encode categorical variables.
- Modeling: Build and evaluate machine learning models for species classification.

### Dataset

The Iris dataset was introduced by R.A. Fisher in 1936 and has become a classic in machine learning and data science. It contains the following columns:

- Id: Unique identifier for each record.
- SepalLengthCm: Length of the sepal in centimeters.
- SepalWidthCm: Width of the sepal in centimeters.
- PetalLengthCm: Length of the petal in centimeters.
- PetalWidthCm: Width of the petal in centimeters.
- Species: The species of the Iris flower (e.g., Iris-setosa, Iris-versicolor, Iris-virginica).

This dataset contains 150 samples with 50 samples from each of the three Iris species.

### Data Quality

**Data Quality Checks**
- Missing Values: No missing values were detected in the dataset.
- Outliers: Outliers were detected in the numerical features using boxplots. These were handled using the IQR method to ensure data quality.

##### Boxplot checks for outliers in the features

![screenshot-github com-2025 01 27-12_28_37](https://github.com/user-attachments/assets/8a08ea50-eb59-4df3-9325-2055a36f8c09)

**Cleaning Steps**
- Standardized the numerical features to bring them to a common scale.
- Encoded the categorical target variable ("Species") as numeric labels using Label Encoding.

### Data Visualization

- Pairplot: A pairplot was created to visualize the relationships between different feature pairs (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm), with species differentiation.
- Histograms: Histograms of the individual features (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm) were plotted to observe their distribution.
- Boxplots: Boxplots were used to check for any outliers in the features and visualize the range of values for each feature.
- Scatterplots: Scatterplots were used to visualize the relationships between the sepal and petal measurements, with color-coding to differentiate the species.
- Correlation Heatmap: A heatmap of the feature correlations was created to understand the linear relationships between features and their potential for classification tasks.

### Key Findings

Feature Relationships:
- There is a strong linear relationship between petal length and petal width.
- Sepal measurements (length and width) show more overlap across species compared to petal measurements, making them less effective for species classification.

Species Distribution:
- Each species exhibits distinct patterns in the feature space, particularly for petal length and width. This makes it possible to visually distinguish between species in scatter plots.

### Next Steps
With the data cleaned and key relationships understood, we can proceed to build machine learning models to predict the species of Iris flowers. The following steps will be taken next:

1. **Model Development**
Develop classification models such as Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest.

2. **Model Evaluation**
Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

3. **Model Tuning**
Tune model hyperparameters to improve performance, if necessary.

### Source

Dataset: [Iris Species Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/iris)
