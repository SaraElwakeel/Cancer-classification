# Cancer Prediction using Logistic Regression

## Overview

This project implements **Logistic Regression** to classify cancerous and non-cancerous cases based on medical data. The workflow includes data exploration, feature selection, normalization, model training, and evaluation.

## Features

- **Data Exploration**: Analyzes dataset distribution and statistics.
- **Feature Selection**: Identifies key attributes for classification.
- **Label Encoding**: Converts categorical variables into numerical format.
- **Data Normalization**: Standardizes feature values for better model performance.
- **Train-Test Splitting**: Divides data into training and test sets.
- **Logistic Regression Model**: Implements logistic regression for classification.
- **Evaluation Metrics**: Uses accuracy, precision, recall, and confusion matrix.

## Installation

To run this project, install the required dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. **Load the Dataset**: Ensure the dataset is available.
2. **Explore and Preprocess Data**: Perform exploratory analysis and normalization.
3. **Train the Model**: Fit the logistic regression model to training data.
4. **Evaluate Performance**: Use classification metrics to assess accuracy.
5. **Make Predictions**: Apply the trained model to new cases.

## Project Structure

```
Cancer_Logistic_Regression/
├── dataset/                      # Cancer dataset
├── models/                       # Trained logistic regression model
├── Cancer_Logistic__regression.ipynb  # Jupyter Notebook with implementation
├── README.md                     # Project documentation
└── requirements.txt              # Dependencies
```

## Future Enhancements

- Implement feature engineering techniques for improved accuracy.
- Compare logistic regression with other classifiers (e.g., SVM, Random Forest).
- Deploy the model as a web application for real-time predictions.

## Contributors

- **Your Name** - Sara elwakeel

## License

This project is open-source and available under the MIT License.

