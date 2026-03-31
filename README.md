# Fake News Detection

## Overview
This project detects whether a news article is *real or fake*.  
It uses *Machine Learning*, *Deep Learning (LSTM)*, and *BERT-based NLP models*.  
The project includes data cleaning, model training, evaluation, and visualizations.  

---

## Dataset
- Two CSV files: `True.csv` and `Fake.csv`.  
- Each file contains news articles and their labels.  
- Dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets).  

---

## Project Structure
Fake-News-Detection/
│
├── data/           # CSV files (True.csv, Fake.csv)
├── notebooks/      # Colab notebook with full code
├── src/            # Optional Python scripts for preprocessing or models
├── requirements.txt  # All Python libraries needed
└── README.md       # Project description

---

## Libraries Used
- pandas, numpy  
- matplotlib, seaborn, wordcloud  
- scikit-learn  
- nltk  
- tensorflow, keras  
- transformers  
- torch (optional, for BERT PyTorch models)  

All libraries are listed in `requirements.txt`.

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Fake-News-Detection.git

#Install required libraries:
pip install -r requirements.txt

#Open the notebook in Colab:
notebooks/Fake_News_Detection.ipynb

#Run all cells to train the models and see results.

#Results
Models: Logistic Regression, Random Forest, LSTM, BERT
Evaluations: Accuracy, Confusion Matrix, Classification Report
Visualizations: WordCloud, training curves

