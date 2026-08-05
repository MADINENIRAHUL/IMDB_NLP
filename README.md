# Sentiment Analysis using Natural Language Processing (NLP)

## Project Overview

This project focuses on preprocessing textual data for sentiment analysis using the IMDb Movie Reviews dataset. The primary objective is to clean and transform raw text into a structured format suitable for machine learning models. Various Natural Language Processing (NLP) techniques are applied to improve the quality of textual data before model training.

---

## Features

- Loaded and explored the IMDb Movie Reviews dataset.
- Converted text to lowercase.
- Removed HTML tags.
- Removed URLs.
- Removed punctuation.
- Removed stop words.
- Removed and converted emojis.
- Performed word and sentence tokenization.
- Applied Regular Expressions for text cleaning.
- Used NLTK for text preprocessing.

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Regular Expressions (re)
- Jupyter Notebook

---

## Dataset

**Dataset Name:** IMDb Movie Reviews Dataset

The dataset contains **50,000** movie reviews labeled as **Positive** or **Negative**.

The dataset is not included in this repository because of its size.

You can download it from:

https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

After downloading, place the file:

```
IMDB Dataset.csv
```

inside the project directory.

---

## Project Workflow

```
IMDb Dataset
      │
      ▼
Load Dataset
      │
      ▼
Text Cleaning
      │
      ├── Lowercase Conversion
      ├── Remove HTML Tags
      ├── Remove URLs
      ├── Remove Punctuation
      ├── Remove Stop Words
      ├── Remove Emojis
      ▼
Tokenization
      ▼
Clean Text
      ▼
Ready for Machine Learning
```

---

## Project Structure

```
Sentiment-Analysis-NLP/
│
├── Sentiment_Analysis.ipynb
├── README.md
├── requirements.txt
└── IMDB Dataset.csv (Download Separately)
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Sentiment-Analysis-NLP.git
```

Move to the project folder

```bash
cd Sentiment-Analysis-NLP
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Results

The project successfully demonstrates an end-to-end NLP preprocessing pipeline for movie review sentiment analysis. The cleaned and normalized text is suitable for training machine learning and deep learning models for sentiment classification.

---

## Future Enhancements

- Feature Extraction using TF-IDF
- Word Embeddings (Word2Vec/GloVe)
- Machine Learning Models
- Deep Learning using LSTM
- BERT-based Sentiment Analysis

---

## Author

**Rahul Madineni**

B.Tech – Computer Science and Engineering

---

## License

This project is licensed under the MIT License.
