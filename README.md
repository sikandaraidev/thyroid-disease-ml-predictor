# Thyroid Disease ML Predictor

This project implements a machine learning pipeline to classify thyroid conditions based on selected lab features. The focus is on a simplified, clinically meaningful prediction model built in Google Colab using Python.

## Objective

To create an intelligent helper tool that can assist in predicting possible thyroid conditions such as hypothyroidism and hyperthyroidism using lab data. The model is designed with a focus on applicability to common testing patterns in the Pakistani healthcare context.

## Features Used
- Age
- Sex
- On thyroxine
- TSH
- T3
- TT4
- T4U
- FTI
- Referral source

## Target Classes
- Hypothyroid
- Hyperthyroid
- Normal

## Best Model
- Random Forest Classifier
- Macro F1 Score (Cross-Validated): **0.9861 ± 0.0088**

## Dataset
The dataset used in this project is publicly available at the UCI Machine Learning Repository:  
[Thyroid Disease Dataset](https://archive.ics.uci.edu/dataset/102/thyroid+disease)

## Research Inspiration
This implementation is based on insights from the following research paper:  
[Sikandar et al., 2022 - Thyroid Disease Prediction Using Machine Learning](https://pmc.ncbi.nlm.nih.gov/articles/PMC9405591/#B22-cancers-14-03914)


## Files Included
- `thyroid_predictor.ipynb`: Main Colab notebook with preprocessing, feature selection, model training, evaluation, and saving.
- `thyroid_rf_model.pkl`: Trained Random Forest model.
- `selected_features.pkl`: Features used during model training.
- `label_map.pkl`: Mapping of diagnosis labels.
- *(Optional)* `preprocessor.pkl`: Scaler/encoder if preprocessing was applied.

## Author
**Sikandar**  
AI/ML Engineer | Python Backend Developer
- LinkedIn: [linkedin.com/in/sikandaraidev](https://linkedin.com/in/sikandaraidev)  
- GitHub: [github.com/sikandaraidev](https://github.com/sikandaraidev)  
- Email: sikandaraidev@gmail.com

## Notes
- This project is intended for educational and portfolio purposes.
- It is not intended to be used as a diagnostic tool.
- A complete deployable web application will be published in a separate repository.
