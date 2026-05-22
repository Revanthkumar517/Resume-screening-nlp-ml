# Resume Screening Using NLP and Machine Learning

## Project Overview
This project classifies resumes into different job categories using Natural Language Processing and Machine Learning.

## Problem Statement
Recruiters receive many resumes in unstructured formats. Manually reviewing every resume takes time. This project helps automate resume screening by cleaning resume text and predicting the resume category.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes
- Matplotlib
- Seaborn

## Project Workflow
1. Load resume dataset
2. Clean resume text
3. Remove URLs, special characters, punctuation, and stopwords
4. Apply lemmatization
5. Convert text into numerical features using TF-IDF
6. Train a machine learning model
7. Predict resume category

## Model Used
- Multinomial Naive Bayes

## Files Included
- `ResumeScreening_using_NLP_and_ML.ipynb` - Main project notebook
- `UpdatedResumeDataSet.csv` - Dataset used for training
- `Mini_Project_Report.docx` - Academic project report
- `requirements.txt` - Required Python libraries

## How to Run
1. Install required libraries:

```bash
pip install -r requirements.txt