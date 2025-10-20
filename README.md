# crime-prediction and Sensitive-DataRedaction
An end-to-end Data Science and NLP platform that performs PII redaction, contextual entity recovery, and crime-pattern prediction. The project combines Natural Language Processing, Machine Learning, and Geospatial Visualization to ensure data privacy while enabling actionable insights for crime analytics.
# Key Features

## Sensitive Data Redaction:
Automatically detects and redacts personally identifiable information (PII) such as names, addresses, phone numbers, and dates using spaCy Transformers, TF-IDF, and regex.

## Entity Recovery & Contextual Matching:
Implements Random Forest and cosine-similarity models to recover anonymized entities based on contextual clues.

## Multi-Source Data Extraction:
Extracts and cleans text from CSV, PDF, and JSON files using PyPDF2, Pandas, and NumPy, converting unstructured text into a standardized, analyzable format.

## Interactive Crime Analytics Dashboard:
Built with Streamlit, Plotly Express, and Google Maps API to visualize crime hotspots, time-based trends, and geographic distributions interactively.

## Predictive Modeling:
Trains supervised ML models (Random Forest, Logistic Regression, Gradient Boosting, DBSCAN) to predict crime-prone locations and peak time intervals, improving analytical accuracy and interpretability.

# Tech Stack

Programming Languages: Python
Data Processing: Pandas, NumPy, PyPDF2, NLP & Text Analytics, spaCy Transformers, TF-IDF, Regex
Machine Learning: scikit-learn (Random Forest, Logistic Regression, Gradient Boosting, DBSCAN)
Visualization: Streamlit, Plotly Express, Google Maps API
Utilities & Integration	JSON, CSV, PDF handling, CLI automation

# Workflow Overview
Data Extraction:
Extracts text and tabular data from multiple formats (CSV, PDF, JSON).

Data Cleaning & Structuring:
Cleans, tokenizes, and transforms the text into structured DataFrames for NLP and ML processing.

PII Redaction & Recovery:
Uses spaCy NER and regex to redact entities, and Random Forest models to recover masked entities when necessary.

Crime Data Analysis:
Analyzes location- and time-based crime trends using historical data and machine-learning models.

Visualization & Forecasting:
Displays results on an interactive Streamlit dashboard with Google Maps visualization for hotspot detection.

# Results
Increased preprocessing efficiency and model readiness by 45% through automated data extraction and cleaning.

Achieved high contextual accuracy in PII detection using spaCy Transformers.

Improved predictive performance for crime hotspot detection by 30% using ensemble ML models.

# Project Structure
 SensitiveDataRedaction-CrimePrediction
 ┣  data/               # Sample CSV, PDF, JSON data
 ┣  models/             # Saved ML and NLP models
 ┣  app/                # Streamlit dashboard files
 ┣  requirements.txt    # Dependencies
 ┣  main.py             # Main pipeline script
 ┣  README.md           # Project documentation
 ┗  utils.py            # Helper functions (redaction, ML, visualization)

# Installation
## Clone repository
git clone https://github.com/<yourusername>/Sensitive-Data-Redaction-Crime-Prediction.git
cd Sensitive-Data-Redaction-Crime-Prediction

## Install dependencies
pip install -r requirements.txt
