# Sentiment-Analysis-of-Internship-Feedback
Developed a Sentiment Analysis of Internship Feedback system to classify intern feedback as positive, neutral, or negative using Natural Language Processing (NLP). The project compares a traditional Logistic Regression model with a Transformer-based (BERT)  to analyze internship feedback.
# Sentiment Analysis of Internship Feedback

## 📌 Overview

This project performs **Sentiment Analysis on Internship Feedback** using Natural Language Processing (NLP). The objective is to classify internship feedback into **Positive, Neutral, or Negative** sentiments based on textual comments provided by interns.

The project compares the performance of a traditional Machine Learning model (**Logistic Regression**) with a Transformer-based Deep Learning model (**BERT**) to evaluate their effectiveness in sentiment classification.

---

## 🚀 Features

* Text preprocessing and cleaning
* Sentiment classification into Positive, Neutral, and Negative
* Logistic Regression implementation using TF-IDF features
* Transformer (BERT) implementation for contextual text understanding
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
  * Confusion Matrix
* Comparison between Machine Learning and Transformer models

---

## 📂 Dataset

* **Dataset:** Employee/Internship Feedback Dataset (Kaggle)
* Contains internship feedback collected from employees/interns.
* Data preprocessing includes:

  * Lowercasing
  * Removing punctuation
  * Removing stopwords
  * Tokenization
  * Combining relevant text fields
  * Label encoding

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Transformers (Hugging Face)
* PyTorch

---

## 🤖 Models Used

### 1. Logistic Regression

* TF-IDF Vectorization
* Fast training
* Lightweight model
* Suitable baseline for sentiment analysis

### 2. BERT (Transformer)

* Pretrained Transformer model
* Fine-tuned on internship feedback dataset
* Captures contextual meaning of text
* Higher accuracy than traditional ML models

---

## 📊 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix




## ▶️ How to Run

1. Clone the repository

```bash
git clone <repository-link>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Train the Logistic Regression model

```bash
python train_logistic.py
```

4. Train the BERT model

```bash
python train_bert.py
```

5. Evaluate the models

```bash
python evaluate.py
```

---

## 📈 Results

The BERT Transformer model achieved higher performance by understanding contextual information in feedback, while Logistic Regression provided a strong baseline with faster training and lower computational requirements.

---

## 🔮 Future Improvements

* Deploy using Flask or FastAPI
* Build a web interface for real-time predictions
* Support multilingual feedback
* Experiment with RoBERTa and DistilBERT
* Hyperparameter optimization
* Use larger internship feedback datasets

---

## 👨‍💻 Author

**Aiman Wazir**

Developed as an NLP project to compare traditional Machine Learning and Transformer-based approaches for internship feedback sentiment analysis.
