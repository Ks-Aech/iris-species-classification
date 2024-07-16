

# Iris Flower Classification

This project implements a machine learning model to classify Iris flowers based on their sepal and petal measurements.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [File Descriptions](#file-descriptions)
5. [Data](#data)
6. [Methodology](#methodology)
7. [Results](#results)
8. [License](#license)

## Project Overview

This project aims to classify Iris flowers into three species (setosa, versicolor, and virginica) using machine learning techniques. We use the famous Iris dataset, apply various data preprocessing steps, perform feature selection, train a Random Forest classifier, and evaluate its performance.

## Installation

To run this project, you need Python 3.7+ and the following libraries:

```
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/iris-classification.git
   cd iris-classification
   ```

2. Run the Jupyter notebook:
   ```
   jupyter notebook iris_classification.ipynb
   ```

3. To make predictions with the trained model, use the `predict_iris_class` function in the notebook.

## File Descriptions

- `iris_classification.ipynb`: Jupyter notebook containing the entire project workflow.
- `dataset.csv`: The Iris dataset used for this project.
- `README.md`: This file, providing an overview of the project.

## Data

The dataset contains 150 samples of Iris flowers, each with four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

And a target variable:
- Class (setosa, versicolor, or virginica)

## Methodology

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Selection
4. Model Selection (Random Forest Classifier)
5. Model Training and Evaluation
6. Prediction on New Data

## Results

Our Random Forest model achieved the following performance metrics:

- Accuracy: 96.67%
- Precision: 96.74%
- Recall: 96.67%
- F1-score: 96.67%

For a detailed analysis of the results, please refer to the Jupyter notebook.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


