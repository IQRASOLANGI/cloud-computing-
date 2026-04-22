# DS Lab Week 7 — Iris Flower Classification with Random Forest

## Overview
This lab walks through a complete machine learning pipeline using the classic Iris dataset in Google Colab.

## Steps Covered
1. **Setup** – Install and verify the Yellowbrick library
2. **Data Loading** – Load the Iris dataset using scikit-learn and convert to a pandas DataFrame
3. **Exploration** – Inspect species distribution and basic statistics
4. **Visualization** – Generate pairplots with Seaborn to explore feature relationships
5. **Model Training** – Split data (80/20) and train a Random Forest Classifier (100 trees)
6. **Evaluation** – Measure accuracy, precision, recall, and F1-score
7. **Save & Load** – Persist the trained model to Google Drive using joblib
8. **Prediction** – Predict the species of a new flower with confidence scores

## Requirements
- Python 3.x
- Google Colab (recommended)
- Libraries: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `yellowbrick`, `joblib`

## How to Run
1. Open the notebook in Google Colab
2. Mount your Google Drive when prompted
3. Run all cells in order from top to bottom

## Output
- Trained model saved as `iris_rf_model.pkl` in `/content/drive/MyDrive/DS_Lab_Week7/`
- Model achieves high accuracy (~97%) on the test set
