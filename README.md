# Term Deposit Customer Prediction

## Overview

This project predicts whether a bank customer will subscribe to a **term deposit** using machine learning techniques. The dataset is preprocessed, encoded, and used to train classification models. The project also includes model evaluation and SHAP-based model interpretability.

## Features

- Data loading and exploration
- Data preprocessing
- Missing value analysis
- Label Encoding
- One-Hot Encoding
- Train-Test Split
- Logistic Regression model
- Random Forest Classifier
- Model evaluation using multiple metrics
- SHAP explainability for feature importance

## Dataset

The project uses the dataset:

- `train 25K.csv`

The target variable is:

- `y` (Whether the customer subscribed to a term deposit)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP

## Project Workflow

1. Load the dataset
2. Perform exploratory data analysis (EDA)
3. Check for missing values
4. Encode categorical variables
5. Apply One-Hot Encoding
6. Split the data into training and testing sets
7. Train Logistic Regression model
8. Train Random Forest Classifier
9. Evaluate model performance
10. Explain predictions using SHAP

## Model Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/term-deposit-prediction.git
```

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap
```

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Term Deposit - Bank Cust..ipynb
```

Execute the cells sequentially.

## Project Structure

```
├── Term Deposit - Bank Cust..ipynb
├── train 25K.csv
├── README.md
```

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost and LightGBM implementation
- Feature engineering
- Model deployment using Flask or Streamlit

## Author

MUHAMMAD SHARIQ

## License

This project is licensed under the MIT License.
