
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

[Colab Link](https://colab.research.google.com/drive/10g9JMr6Bl8zTZUIXDSHDaZPVXdHn1hkW#scrollTo=0iZUYjYZtQXR)

---

### `sentiment_classification_DL.ipynb`
**Description**:  
Applies deep learning techniques for sentiment classification using:  
- Long Short-Term Memory (LSTM) networks  

**Key Features**:  
- Implementation of LSTM for processing textual data.  
- Performance metrics analysis for DL-based models.  

[Colab Link](https://colab.research.google.com/drive/1gycn0KPqzAg0prAqP2Kvagt5h9-Z1D7e#scrollTo=yQ-7wgJDtRT6)

---

### `Topic_Modeling_BERT.ipynb`
**Description**:  
Performs topic modeling on the IMDB 50k reviews dataset using BERTopic.  

**Key Features**:  
- Extraction of topics to discover common themes in reviews.  
- Insights into aspects such as acting, screenplay, and music.  

[Colab Link](https://colab.research.google.com/drive/1x18GCZbdKbODB5kRYddJIHlZuCwYmU92#scrollTo=nOsA37CatOhU)

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

[Colab Link](https://colab.research.google.com/drive/1cJkCDYMUJvpjZ2g2tinOr36ni3OsoX4a#scrollTo=x0x-W6ZE1DOI)

---

## Installation
To set up the environment and run the notebooks, follow these steps:  

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
pip install -r requirements.txt
