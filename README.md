# Assignment-8-SF
Supervised Learning Classification
# Credit Card Fraud Detection Notebook

This repository contains a Jupyter Notebook for detecting credit card fraud using machine learning techniques.

## Dataset

The notebook uses the [creditcard.csv](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) dataset, which contains anonymized transactions labeled as **fraudulent** or **legitimate**.

## Features

* `Time` and `Amount` of each transaction
* PCA-transformed features `V1` to `V28`
* Target variable: `Class` (0 = legitimate, 1 = fraud)

## Notebook Contents

1. **Data Preprocessing and EDA**: Missing values handling, scaling, class imbalance analysis, and visualization.
2. **Model Training and Evaluation**: Logistic Regression, Random Forest, evaluation metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC), and interpretation.
3. **Deployment & Monitoring Strategy**: Guidelines for production deployment and ongoing monitoring.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Shufen-Yin/Assignment-8-.git
   ```
2. Open the notebook in Jupyter or Google Colab.
3. Ensure the dataset `creditcard.csv` is in the same folder as the notebook.
4. Run the notebook cells sequentially.

## Requirements

* Python 3.x
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* imbalanced-learn (for SMOTE)

## License

This project is open-source and available under the MIT License.

