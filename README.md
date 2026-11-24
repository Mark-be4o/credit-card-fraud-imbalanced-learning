# Credit Card Fraud Imbalanced Learning

Credit card fraud detection: handling extreme class imbalance with SMOTE, undersampling and class weights.

## What it does

Fraud detection on the highly imbalanced credit card dataset (about 0.17% fraud). Compares a baseline model with class weighting, SMOTE oversampling and random undersampling. The notebook also contains SQL revision notes and a short Transformers section.

## Files

- `fraud_detection_imbalanced_data.ipynb`

## Tools

scikit-learn, imbalanced-learn, pandas, numpy, matplotlib, seaborn, Hugging Face Transformers, kagglehub

## Dataset

[Credit Card Fraud Detection (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Baseline: fraud recall 0.655, precision 0.822. SMOTE: recall 0.85, precision 0.13. Undersampling: recall 0.88, precision 0.05. Oversampling and undersampling raise recall at the cost of precision.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
