# IMDB Sentiment Analysis

A sentiment classification project using classical machine learning and NLP preprocessing techniques on the IMDB movie reviews dataset.

## Approach

The text data was processed through the following pipeline:

- Text cleaning and normalization
- Spell correction using SymSpell
- Stopword removal
- Lemmatization using spaCy
- TF-IDF feature extraction

## Models Implemented

Three machine learning classifiers were trained and evaluated:

- Support Vector Machine (SVM)
- Multinomial Naive Bayes
- Logistic Regression

## Tools & Libraries

- Python
- Pandas
- Scikit-learn
- spaCy
- SymSpell
- NLTK
- Matplotlib
- Seaborn

## Files

- `sentiment_analysis_svm.ipynb` — SVM implementation
- `sentiment_analysis_multinomial_nb.ipynb` — Multinomial Naive Bayes implementation
- `sentiment_analysis_logistic_regression.ipynb` — Logistic Regression implementation

## Objective

The goal of this experiment was to understand the complete NLP workflow, from text preprocessing and feature extraction to training classical machine learning models for sentiment classification.

## Dataset Workflow

The original IMDB dataset is not included in this repository due to its large size.

The workflow for running this project is:

1. Download the IMDB Movie Reviews dataset.
2. Run the preprocessing experiments to clean and transform the raw review data.
3. The preprocessing notebooks generate processed datasets used for model training.
4. Move the generated processed datasets into the `data/` directory.
5. Run the finalized model notebooks for:
   - Support Vector Machine (SVM)
   - Multinomial Naive Bayes
   - Logistic Regression

Workflow:

Raw Dataset → Preprocessing Experiments → Processed Dataset → Final Model Experiments