# NLP-Based Sentiment Analysis of Movie Reviews Using TF-IDF and Logistic Regression

A mini NLP project that classifies movie reviews as **positive** or **negative** using
TF-IDF for feature extraction and Logistic Regression for classification.

## Overview
- **Dataset:** IMDB Dataset of 50K Movie Reviews ([Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews))
- **Technique:** TF-IDF + Logistic Regression
- **Result:** 89.40% accuracy, 89.49% F1-score on the test set

For the full write-up (problem statement, methodology, results, limitations, future scope),
see the report in `report/`.

## How to Run
1. Clone this repository or download `nlp_project.ipynb`.
2. Download the dataset manually from
   [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
   and place `IMDB Dataset.csv` in the same folder as `nlp_project.ipynb`.
3. Install dependencies:
   pip install -r requirements.txt
5. Run the script:
   python nlp_project.ipynb

   The script loads the local CSV, preprocesses the data, trains the model, and
   prints evaluation results.

## Project Structure
NLP-Project/
├── README.md
├── source_code.py
├── dataset/
│ └── README.md # dataset info + source link (raw data not included)
├── screenshots/ # confusion matrix, sample outputs
├── report/ # full project report (PDF/DOCX)
└── requirements.txt


## Author
Abhishek V Nair | 24UBC103 | BCA
