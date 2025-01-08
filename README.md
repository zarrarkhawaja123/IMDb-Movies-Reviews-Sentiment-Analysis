
# Sentiment Analysis and Topic Modeling on IMDB 50k Reviews

## Overview
This repository contains various projects focused on sentiment analysis and topic modeling, utilizing machine learning (ML), deep learning (DL), and natural language processing (NLP) techniques. The IMDB 50k reviews dataset is used to preprocess, analyze, and derive meaningful insights about movie reviews.

---

## Repository Structure

### `sentiment_ML.ipynb`
**Description**:  
Performs sentiment analysis on the IMDB 50k reviews dataset using:  
- Naive Bayes (NB)  
- Logistic Regression (LR)  

**Key Features**:  
- Comparison of metrics like accuracy, precision, recall, and F1 score for both models.  
- Insights into model performance for classification tasks.  

[Colab Link](https://colab.research.google.com/github/Ifham-Ansari/IMDB-dataset-Sentiment-Analysis-Topic-Modeling/blob/main/sentiment_ML.ipynb)

---

### `sentiment_classification_DL.ipynb`
**Description**:  
Applies deep learning techniques for sentiment classification using:  
- Long Short-Term Memory (LSTM) networks  

**Key Features**:  
- Implementation of LSTM for processing textual data.  
- Performance metrics analysis for DL-based models.  

[Colab Link](https://colab.research.google.com/github/Ifham-Ansari/IMDB-dataset-Sentiment-Analysis-Topic-Modeling/blob/main/sentiment_classification_DL.ipynb)

---

### `Topic_Modeling_BERT.ipynb`
**Description**:  
Performs topic modeling on the IMDB 50k reviews dataset using BERTopic.  

**Key Features**:  
- Extraction of topics to discover common themes in reviews.  
- Insights into aspects such as acting, screenplay, and music.  

[Colab Link](https://colab.research.google.com/github/Ifham-Ansari/IMDB-dataset-Sentiment-Analysis-Topic-Modeling/blob/main/Topic_Modeling_BERT.ipynb)

---

### `index.ipynb`
**Description**:  
A consolidated notebook that combines all analyses and comparisons in one place.  

**Key Features**:  
- **Exploratory Data Analysis (EDA)**:  
  - Visualizations of demographic and textual data.  
  - Identification of the best and worst-reviewed movies by genre.  

- **Sentiment Analysis Comparison**:  
  - Metrics comparison across Naive Bayes, Logistic Regression, and LSTM models.  

- **Topic Modeling with BERTopic**:  
  - Key topics extracted and visualized from reviews.  

[Colab Link](https://colab.research.google.com/github/Ifham-Ansari/IMDB-dataset-Sentiment-Analysis-Topic-Modeling/blob/main/index.ipynb)

---

## Installation
To set up the environment and run the notebooks, follow these steps:  

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
pip install -r requirements.txt
