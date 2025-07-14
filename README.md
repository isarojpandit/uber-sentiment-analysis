# 🚕 Uber Review Sentiment Analysis (NLP + Deep Learning)

This project performs sentiment analysis on Uber app reviews using traditional NLP tools and deep learning models. It compares the performance of VADER, TextBlob, and BERT (RoBERTa), and implements a BiLSTM model to predict future sentiment trends over time.

## 🔍 Features

- Text cleaning: emoji handling, lemmatization, stemming
- Sentiment classification with:
  - VADER
  - TextBlob
  - BERT (`cardiffnlp/twitter-roberta-base-sentiment`)
- Forecasting sentiment trends using a BiLSTM model
- Time-series preparation & normalization
- Model evaluation with accuracy & classification reports

## 📁 Folder Structure

- `notebooks/`: Jupyter Notebook for full exploratory work and experiments
- `src/`: Modular Python scripts for preprocessing, modeling, and evaluation
- `data/`: Contains the dataset 
- `reports/`: Output reports and performance comparison

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/isarojpandit/uber-sentiment-analysis.git
cd uber-sentiment-analysis

