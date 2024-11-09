# Iris Species Data Exploration

### Overview

This project demonstrates introductory data exploration techniques using the Iris dataset. The dataset contains information about the Iris flower species, specifically the physical measurements of the flowers and their species classification. The goal of this project is to load the data, visualize the distribution of species, and understand the relationships between various features through scatter plots and histograms.

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

### Source

https://www.kaggle.com/datasets/uciml/iris
