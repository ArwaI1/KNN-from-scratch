# KNN Implementation from Scratch

This project demonstrates how to implement the K-Nearest Neighbors (KNN) algorithm from scratch and compares its performance with the scikit-learn library's implementation using the Iris dataset.

## Introduction
The K-Nearest Neighbors (KNN) algorithm is a straightforward yet efficacious classification algorithm. This project endeavors to furnish a thorough guide on crafting a KNN algorithm from the ground up and juxtapose its efficacy with the renowned scikit-learn library.

## Installation
Ensure the required libraries are installed on your machine. These libraries are pivotal for the project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

To install these dependencies, execute the following command:
pip install -U scikit-learn pandas numpy matplotlib seaborn

## Dataset
The venerable Iris dataset serves as the cornerstone of this project. It encompasses 150 samples of iris flowers, each annotated with four features (sepal length, sepal width, petal length, petal width) and a class label indicative of the flower's species.

## Data Exploration and Preprocessing
Prior to deploying the KNN algorithm, the dataset undergoes a series of exploratory and preprocessing steps:
- **Dataset Information**: Unveil fundamental insights about the dataset.
- **Head and Description**: Inspect initial rows and statistical summations of the dataset.
- **Class Distribution**: Ascertain the equilibrium within class distributions.
- **Missing Data**: Probe for any absent values.
- **Duplicates**: Detect and excise duplicate records.
- **Feature and Label Separation**: Partition the dataset into features (X) and labels (Y).
- **Data Splitting**: Diverge the dataset into training and test sets (80% training, 20% testing).
- **Normalization**: Appropriate normalization of features to ensure equitable distance computations in KNN.

## KNN Implementation
The implementation of the KNN algorithm from scratch encompasses the ensuing phases:
1. **Calculate Euclidean Distance**: Gauge the distance amid the test instance and every training point.
2. **Find Nearest Neighbors**: Isolate the k-nearest neighbors to the test instance.
3. **Majority Voting**: Decipher the class of the test instance based on the prevalent vote amongst its nearest neighbors.

## Comparison with Scikit-learn
This segment delineates the bench-marking of our bespoke KNN algorithm against the scikit-learn KNN model by:
- **Training and Prediction**: Instruct the scikit-learn KNN model and forecast on the test set.
- **Accuracy Comparison**: Evaluate and contrast the preciseness of both the implementations.

## Visualization
Employing visual aids to demystify the dataset and the analysis outcomes:
- **Pair Plot**: Illustrate interdependencies amongst features before and after normalization.
- **Correlation Heatmap**: Illustrate correlations amidst features.

## Results
This division encapsulates the followings:
- **Predictions**: Showcase predictions yielded by both the custom-made and scikit-learn KNN algorithms.
- **Accuracy**: Compare the accuracy scores ascertained by both algorithms.
- **Testing with Different k Values**: Present results across divergent k values (e.g., 3, 5, 7) to ascertain their impact on accuracy.
