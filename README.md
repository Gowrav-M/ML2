
# Iris Species Classification with Decision Trees

This project demonstrates a complete machine learning workflow to classify Iris flower species using a Decision Tree Classifier. It includes data loading, exploratory analysis, model training, evaluation, and tree visualization.

## Project Overview

The goal is to predict the species of an iris flower based on its physical measurements: sepal length, sepal width, petal length, and petal width.

## Features

*   **Data Loading:** Uses the classic Scikit-Learn Iris dataset.
*   **Exploratory Data Analysis (EDA):** Verifies data integrity and checks for missing values.
*   **Model Training:** Employs a `DecisionTreeClassifier` with entropy-based splitting.
*   **Visualization:** Generates a visual representation of the decision tree logic using Graphviz.

## Getting Started

### Prerequisites

You will need the following Python libraries installed:

```bash
pip install pandas scikit-learn graphviz
```

### Workflow

1.  **Data Preparation:** The dataset is loaded and converted into a Pandas DataFrame for easy manipulation.
2.  **Preprocessing:** Data is split into training (80%) and testing (20%) sets to ensure unbiased evaluation.
3.  **Model Configuration:** A Decision Tree is initialized with a `max_depth` of 4 to prevent overfitting.
4.  **Training:** The model is fitted using the training data features (`irisIndTrain`) and targets (`irisDeptrain`).
5.  **Prediction & Evaluation:** The model predicts species for the test set, and accuracy can be verified by comparing `PredictedData` against `irisDeptest`.
6.  **Visualization:** The logic paths of the tree are exported and rendered using Graphviz.

## Results

The model creates clear decision boundaries based on petal dimensions, which are the most significant features for separating the Setosa, Versicolor, and Virginica species.

## License

This project is open-source and available under the MIT License.
```
