# Airline Customer Satisfaction Prediction using XGBoost

## Overview

This project focuses on predicting airline customer satisfaction using the powerful XGBoost Classifier. The model is trained on an anonymized dataset containing 103,904 entries with 25 features, and its performance is evaluated on a test set comprising 25,976 entries. The aim is to predict whether a customer will have a satisfying experience with a flight.

## Key Features

- Utilizes the XGBoost Classifier for accurate predictions.
- Dataset includes personal data, flight amenities, flight delay details, and travel details.
- Implements feature selection, data preprocessing, and target balancing.
- Evaluation metrics include a confusion matrix and a detailed classification report.

## Dataset

- **Training Dataset:** 103,904 entries
- **Testing Dataset:** 25,976 entries

## Features

- **Non-Numeric Features:** 4
- **Numeric Features:** 21

## Data Preprocessing

1. Null values are handled using mean or mode imputation.
2. Alpha-numeric features are one-hot encoded.
3. Target encoding is applied to the satisfaction variable.
4. Correlation matrix and multicollinearity checks are performed.
5. Feature importance is assessed using the ANOVA F-statistic.

## Model Training

- XGBoost Classifier is trained on the preprocessed data.
- Features are rescaled to ensure model efficiency.

## Model Evaluation

- Confusion matrix and classification report provide insights into the model's performance.
- Target balancing is employed to address class imbalance.

## How to Use

1. Clone the repository.
2. Run the provided Jupyter Notebook or Python script.
3. Input relevant data to predict customer satisfaction.

## Installation
```bash
git clone https://github.com/OmBaval/Airline-Customer-Satisfaction
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Author

- **OM BAVAL**
- LinkedIn: [ombaval](https://www.linkedin.com/in/ombaval/)
- Email: ombaval@gmail.com

Feel free to explore, use, and contribute to this airline customer satisfaction prediction model!
