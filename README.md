# Multilingual Sentiment Analysis 🎬

## 📌 Overview

This project is part of the **Udacity Deep Learning Nano Degree** program.
The goal is to analyze the **sentiment of movie reviews** written in three different languages — **English, French, and Spanish**.

The project demonstrates an **end-to-end NLP workflow**:

* Data preprocessing and merging multiple CSV files
* Translating non-English reviews into English using pretrained Transformers
* Performing sentiment classification (positive/negative) with Hugging Face models
* Storing the results in a single structured dataframe and exporting as CSV

---

## 🛠️ Tech Stack

* **Python 3.7+**

**Core Libraries**

* [Pandas](https://pandas.pydata.org/) – data manipulation and integration

**Natural Language Processing**

* [Hugging Face Transformers](https://huggingface.co/transformers/) – pretrained models for translation & sentiment analysis
* [PyTorch](https://pytorch.org/) – backend for Transformer models

**Development Environment**

* [Jupyter Notebook](https://jupyter.org/) – interactive experimentation

---

## 📊 Dataset

* **30 movies total**

  * 10 English reviews → `movie_reviews_eng.csv`
  * 10 French reviews → `movie_reviews_fr.csv`
  * 10 Spanish reviews → `movie_reviews_sp.csv`
* Each file includes: Title, Year, Synopsis, Review, and Original Language

Final dataframe includes:

* `Title`, `Year`, `Synopsis`, `Review`, `Original Language`, `Sentiment`

---

## 🚀 Project Workflow

1. **Data Integration**

   * Load CSV files into Pandas
   * Merge into a single dataframe with language indicator

2. **Translation**

   * Use Hugging Face pretrained translation models
   * Convert French & Spanish reviews/synopses → English

3. **Sentiment Analysis**

   * Apply pretrained sentiment classification model
   * Add sentiment results (Positive/Negative) to dataframe

4. **Output**

   * Export final dataframe as CSV with complete annotations

---

## 📈 Results

* Successfully translated **20 non-English reviews** into English
* Classified sentiment of all **30 movie reviews**
* Final CSV includes multilingual metadata and sentiment column
* Demonstrated pipeline integration of **data cleaning + translation + sentiment classification**

---

## 🎓 Acknowledgements

* Project completed as part of the **Udacity Deep Learning Nano Degree**
* Pretrained models from [Hugging Face Transformers](https://huggingface.co/transformers/)
