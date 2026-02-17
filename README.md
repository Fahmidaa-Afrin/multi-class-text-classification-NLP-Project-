# Multi-Class Text Classification: Q&A Dataset
**Course:** CSE440: Natural Language Processing II  
**Project Type:** Course Project  

**Short Description:**  
Multi-class Q&A text classification using Machine Learning and Neural Network models with multiple word embeddings.

---

## Files

* `QnA_TextClassification.ipynb` – Google Colab notebook with all code, experiments, and visualizations  
  

---

## Project Description

This project explores **multi-class text classification** using a Q&A dataset. We compare the performance of **Machine Learning models (Random Forest, Logistic Regression, Naive Bayes)** and **Neural Network models (DNN, SimpleRNN, GRU, LSTM, and their bidirectional variants)** across multiple word representations including **Bag of Words, TF-IDF, GloVe, and Skip-gram embeddings**.

---

## Dataset

The dataset is provided by the course (CSE440). It is pre-split into training (80%) and testing (20%) sets.

> **Note:** Dataset files are not included here due to course restrictions.

---

## Methodology

1. **Exploratory Data Analysis (EDA):** Analyze the dataset to identify patterns and class distributions.  
2. **Preprocessing:** Stopword removal, stemming/lemmatization, and other cleaning steps.  
3. **Word Representations:** Implement BoW, TF-IDF, GloVe, and Skip-gram embeddings.  
4. **Model Training:**  
   * Random Forest, Logistic Regression, Naive Bayes  
   * DNN, SimpleRNN, GRU, LSTM, and their bidirectional variants  
5. **Hyperparameter Tuning:** Manual tuning guided by validation performance.  
6. **Evaluation Metrics:** Accuracy, macro/weighted F1-score, confusion matrix, and classification report.

---

## Results

* Comparative performance of all ML and NN models with each word representation  
* Visualizations and tables included in the notebook and report

---

## How to Use

1. Open `QnA_TextClassification.ipynb` in **Google Colab** (or Jupyter Notebook if preferred).  
2. Run all cells sequentially to reproduce preprocessing, training, and evaluation.  
3. Refer to `qna_text_classification_report.pdf` for detailed explanations, results, and analysis.

---


